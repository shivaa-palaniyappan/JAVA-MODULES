# Ex.No:4(E) DESIGN PATTERN ---- BEHAVIOUR PATTERN
## QUESTION:
Create a ChatRoom class (mediator) and two users (colleagues) who send and receive messages through it. No direct communication allowed. (Mediator Pattern)
## AIM:
To implement the Mediator Design Pattern using a ChatRoom class where users communicate indirectly through a mediator..


## ALGORITHM :
1. Start the program.
2. Import the package java.util.*.
3. Create a ChatRoom class as the mediator.
4. Maintain a collection of registered users in the ChatRoom.
5. Create a User class with methods to send and receive messages.
6. Register users with the ChatRoom.
7. Read the sender, receiver, and message from the user.
8. Send messages through the ChatRoom mediator.
9. Display the received messages.
10. Stop the program.



## PROGRAM:

```java
/*
Program to implement Behaviour Pattern using Java (Observer Pattern)
Developed by: PRASANNA I
RegisterNumber: 212223220079
*/
```

## SOURCE CODE:

```
import java.util.*;

class ChatRoom {
    private Map<String, User> users = new HashMap<>();

    // Register users
    public void register(User user) {
        users.put(user.getName(), user);
    }

    // Send message through mediator
    public void sendMessage(String from, String to, String message) {
        User receiver = users.get(to);

        if (receiver != null) {
            receiver.receive(from, message);
        }
    }
}

class User {
    private String name;
    private ChatRoom chatRoom;

    public User(String name, ChatRoom chatRoom) {
        this.name = name;
        this.chatRoom = chatRoom;
        chatRoom.register(this);
    }

    public void send(String to, String message) {
        chatRoom.sendMessage(name, to, message);
    }

    public void receive(String from, String message) {
        System.out.println(from + " to " + name + ": " + message);
    }

    public String getName() {
        return name;
    }
}

public class ChatApp {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        ChatRoom room = new ChatRoom();

        String user1 = sc.nextLine();
        String user2 = sc.nextLine();

        User u1 = new User(user1, room);
        User u2 = new User(user2, room);

        int n = Integer.parseInt(sc.nextLine());

        for (int i = 0; i < n; i++) {
            String sender = sc.nextLine();
            String receiver = sc.nextLine();
            String message = sc.nextLine();

            if (sender.equals(u1.getName())) {
                u1.send(receiver, message);
            } else if (sender.equals(u2.getName())) {
                u2.send(receiver, message);
            }
        }

        sc.close();
    }
}
```




## OUTPUT:

<img width="1198" height="740" alt="image" src="https://github.com/user-attachments/assets/17da8af6-4d0b-41b6-8006-aef7190247a9" />




## RESULT:

Thus, the Mediator Design Pattern was implemented successfully using a ChatRoom mediator that enables communication between users without direct interaction.
