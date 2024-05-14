# 📚 Week 5

## 🌈 Enums

### Understanding Enums
- **What are Enums?**
  - Enums (short for "enumerations") are a special type in Java used to define a fixed set of constants.
  - They provide a way to represent a group of named constants in a more expressive and type-safe manner.

### Defining Enums
- **Enum Declaration:**
  ```java
  public enum DaysOfWeek {
      MONDAY,
      TUESDAY,
      WEDNESDAY,
      THURSDAY,
      FRIDAY,
      SATURDAY,
      SUNDAY
  }
  ```

- **Using Enums:**
  ```java
  DaysOfWeek today = DaysOfWeek.MONDAY;
  if (today == DaysOfWeek.SATURDAY || today == DaysOfWeek.SUNDAY) {
      System.out.println("It's the weekend!");
  }
  ```

### 🎨 Practical Exercise: Implementing Enums
- **Task:** Create an enum to represent the different states of a traffic light.
- **Instructions:**
  - Define an enum called `TrafficLight` with constants for `RED`, `YELLOW`, and `GREEN`.
  - Write a Java program that simulates the behavior of a traffic light using the enum.

### 💡 Discussion
- Discuss the benefits of using enums over traditional constants in terms of readability and maintainability.
- Explore advanced features of enums, such as associating values or methods with enum constants.

## 🗺️ HashMap and HashSet

### Understanding HashMap
- **What is HashMap?**
  - HashMap is a class in Java that implements the Map interface.
  - It stores key-value pairs, allowing efficient retrieval of values based on their corresponding keys.

### Basic Operations with HashMap
- **Creating a HashMap:**
  ```java
  Map<String, Integer> map = new HashMap<>();
  ```

- **Adding Elements:**
  ```java
  map.put("key1", 10);
  map.put("key2", 20);
  ```

- **Retrieving Elements:**
  ```java
  int value = map.get("key1");
  ```

### Understanding HashSet
- **What is HashSet?**
  - HashSet is a class in Java that implements the Set interface.
  - It stores a collection of unique elements, ensuring no duplicates are allowed.

### Basic Operations with HashSet
- **Creating a HashSet:**
  ```java
  Set<String> set = new HashSet<>();
  ```

- **Adding Elements:**
  ```java
  set.add("apple");
  set.add("banana");
  ```

- **Checking for Existence:**
  ```java
  boolean contains = set.contains("apple");
  ```

### 🌍 Practical Exercise: Word Frequency Counter
- **Task:** Implement a program that counts the frequency of words in a given text using HashMap and HashSet.
- **Instructions:**
  - Create a HashMap to store word frequencies, where the keys are unique words and the values are their counts.
  - Use a HashSet to keep track of unique words encountered.
  - Process the input text, updating the HashMap and HashSet accordingly.
  - Print the word frequencies.
  - Print the uniques words.

``` text
Far out in the uncharted backwaters of the unfashionable end of the western spiral arm of the Galaxy
lies a small unregarded yellow sun.
Orbiting this at a distance of roughly ninety-two million miles is an utterly insignificant little blue green
planet whose ape-descended life forms are so amazingly primitive that they still think digital watches are a
pretty neat idea.
This planet has - or rather had - a problem, which was this: most of the people on it were unhappy for
pretty much of the time. Many solutions were suggested for this problem, but most of these were largely
concerned with the movements of small green pieces of paper, which is odd because on the whole it wasn't
the small green pieces of paper that were unhappy.
And so the problem remained; lots of the people were mean, and most of them were miserable, even the
ones with digital watches.
Many were increasingly of the opinion that they'd all made a big mistake in coming down from the trees
in the first place. And some said that even the trees had been a bad move, and that no one should ever have
left the oceans. 
```

### 💡 Discussion
- Discuss the differences between HashMap and HashSet and when to use each one.
- Explore the performance characteristics of HashMap and HashSet in terms of time complexity.

## 📊 Class Diagrams and Use Case Diagrams

### Understanding Class Diagrams
- **What are Class Diagrams?**
  - Class diagrams are a type of UML (Unified Modeling Language) diagram used to visually represent the structure of a system.
  - They show the classes, their attributes, methods, and relationships between classes.

### Basic Elements of Class Diagrams
- **Classes:**
  - Represented by rectangles divided into three sections: class name, attributes, and methods.

- **Relationships:**
  - Association: A solid line indicating a relationship between two classes.
  - Aggregation: A hollow diamond arrow indicating a "has-a" relationship.
  - Composition: A filled diamond arrow indicating a strong "has-a" relationship.
  - Inheritance: A hollow triangle arrow indicating an "is-a" relationship.

### Understanding Use Case Diagrams
- **What are Use Case Diagrams?**
  - Use case diagrams are a type of UML diagram used to capture the functional requirements of a system.
  - They show the actors (users or external systems) and the use cases (functionalities) they interact with.

### Basic Elements of Use Case Diagrams
- **Actors:**
  - Represented by stick figures, representing users or external systems interacting with the system.

- **Use Cases:**
  - Represented by ovals, describing a specific functionality or interaction between an actor and the system.

### 🎨 Practical Exercise: Designing a Class Diagram and Use Case Diagram
- **Task:** Create a class diagram and use case diagram for a simple online shopping system.
- **Instructions:**
  - Identify the main classes, attributes, and methods involved in the online shopping system.
  - Create a class diagram representing the structure of the system.
  - Identify the actors and use cases for the online shopping system.
  - Create a use case diagram showing the interactions between actors and use cases.

### 💡 Discussion
- Discuss the importance of class diagrams and use case diagrams in software design and development.
- Explore how these diagrams facilitate communication and understanding among team members.

## 🧩 Practical Project: Library Management System

### Project Description
- Develop a simple library management system using the concepts learned in Week 5.
- The system should allow librarians to manage books, members, and borrowing/returning of books.

### Project Requirements
- Use enums to represent book categories or member types.
- Implement a HashMap to store book information, with the book ID as the key and book details as the value.
- Use a HashSet to keep track of unique member IDs.
- Create class diagrams to represent the structure of the library management system.
- Design use case diagrams to capture the interactions between librarians, members, and the system.

### 🚀 Implementation Steps
- Step 1: Define the necessary enums for book categories and member types.
- Step 2: Create classes for Book and Member with appropriate attributes and methods.
- Step 3: Implement a HashMap to store book information and a HashSet to store unique member IDs.
- Step 4: Develop functionality for adding books, registering members, borrowing books, and returning books.
- Step 5: Create class diagrams and use case diagrams for the library management system.
- Step 6: Test the system with sample data and ensure it meets the project requirements.

### 💡 Discussion
- Discuss how the concepts learned in Week 5 (Enums, HashMap, HashSet, Class Diagrams, Use Case Diagrams) are applied in the library management system project.
- Explore potential enhancements or additional features that could be added to the system.