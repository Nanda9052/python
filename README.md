// Person.java
class Person {
    // Attributes
    private String name;
    private int age;

    // Constructor
    public Person(String name, int age) {
        this.name = name;
        this.age = age;
    }

    // Getter methods
    public String getName() {
        return name;
    }

    public int getAge() {
        return age;
    }

    // Method to display person details
    public void displayDetails() {
        System.out.println("Name: " + name + ", Age: " + age);
    }
}

// Main class
public class Main {
    public static void main(String[] args) {
        // Creating Person objects
        Person person1 = new Person("Alice", 30);
        Person person2 = new Person("Bob", 25);

        // Displaying their details
        person1.displayDetails();
        person2.displayDetails();
    }
}

