# gitlek

```javascript
let a = "hello";
```
```java
public class Main {
  public static void main(String[] args) {
    System.out.println("Hello World");
  }
}
```

![alt text](https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2886&q=80) 

[Länk till Google](https://www.google.com)

| Table | Table |
| ----------- | ----------- |
| Table | Table |
| Table | Table |

**This is bold text**
*This is italic text*

:smiling_imp: dont mess with me

* * *

- This is one
- This is two
- This is three

> “Be who you are and say what you feel, because those who mind don’t matter and those who matter don’t mind.”

– Bernard M. Baruch

This is a ``highlighted``word :) 

# Sequence Diagram
```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```
# Class diagram
```mermaid
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
```
# ER Diagram
```mermaid
erDiagram
    CAR ||--o{ NAMED-DRIVER : allows
    CAR {
        string allowedDriver FK "The license of the allowed driver"
        string registrationNumber
        string make
        string model
    }
    PERSON ||--o{ NAMED-DRIVER : is
    PERSON {
        string driversLicense PK "The license #"
        string firstName
        string lastName
        int age    
}
```
## Sequence diagram - jwt

```mermaid
sequenceDiagram
    actor Client
    Client->>Server: Wants to autenticate, sends over email and password.
    Note right of Server: Checks email and password
    Server-->>Client: Sends back encrypted JWT.
    Note left of Client: Stores JWT in browser.
    Client->>Server: Requests access to webpage.
    Note right of Server: Authorizes
    Server-->>Client: If authorized, sends back requested files
```

