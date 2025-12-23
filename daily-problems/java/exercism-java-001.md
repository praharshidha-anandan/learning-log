# Exercism - Daily Problem 001: Hello, World!

## Solution Overview:
- "Hello, World!" is the traditional first exercise that most people beginning a new language do.
- Here, "Hello, World!" is implemented using the class `Greeter`, which calls the method `getGreeting`, which returns the string "Hello, World!"

## Solution Code:
```java
class Greeter {
    String getGreeting() {
        return "Hello, World!";
    }
}
```

## Output:
```
Hello, World!
```
As someone with previous experience of working in Python, this gives me the same energy as:
```python
class Greeter:
    def getGreeting(self):
        return "Hello, World!"
```
In which `self` lets the `getGreeting` method access the instance.
Both the Java and Python implementations will return the same output.

## Note:
While in Java the usual way for beginners to learn printing statements is:
```java
public class Main{
    public static void main(String args[]){
        System.out.println("Hello, World!");
    }
}
```
This is the more static implementation that uses the `main` method which every program needs to run standalone.
This will be the correct way to run standalone programs, yes.
But from a bit of research, I understood that Exercism has an automated testing environment that doesn't require me to run the whole `main` method and only implement a specific method defined inside the `Greeter` class they had already created for testing.
The evaluator program will call the `getGreeting` method inside it's own script.
Also noted that this is a clever way to get beginners started on Java OOP.