<div align="center"><h1>Day 7 - Inheritance Adventure: Building on Blueprints!</h1></div>

Welcome to Day 7! Today, we’re exploring **inheritance**—a key concept in Java that lets you build new classes based on existing ones. It’s like taking a great blueprint and adding some extra features to make it even better. Let’s dive in!

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> What is Inheritance?

Imagine you have a basic robot blueprint (class) that has some cool features. Now, you want to create a new type of robot that has all the features of the basic one, plus some extra abilities. Instead of starting from scratch, you use inheritance to build on the existing blueprint.

In Java, **inheritance** allows one class (called a **subclass** or **child class**) to inherit the properties and methods of another class (called a **superclass** or **parent class**). This helps you reuse code and create more specialized classes.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> Creating a Superclass

Let’s start with a simple superclass named Animal:

![java banner](https://github.com/AdyaAgr/20-Days-of-Java/blob/main/images/Day%201.png)

**What’s Inside?**

*   **String name;**: Property for the animal’s name.
*   **void eat()**: Method that prints a message when the animal eats.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> Creating a Subclass

Now, let’s create a subclass named Dog that inherits from Animal:

![java banner](https://github.com/AdyaAgr/20-Days-of-Java/blob/main/images/Day%201.png)

**What’s Happening?**

*   **Dog extends Animal**: This line means that Dog is a subclass of Animal. It inherits all the properties and methods from Animal.
*   **String breed;**: A new property specific to Dog.
*   **void bark()**: A new method specific to Dog.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> Why Use Inheritance?

1.  **Code Reuse:** You can reuse code from the superclass, so you don’t need to rewrite it.
2.  **Organization:** It helps you organize your classes in a hierarchy.
3.  **Flexibility:** You can create more specialized classes that build on existing ones.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> Overriding Methods

Sometimes, you might want to change how a method works in a subclass. This is called **overriding**. Here’s how you can do it:

![java banner](https://github.com/AdyaAgr/20-Days-of-Java/blob/main/images/Day%201.png)

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> What’s New?

*   **@Override**: This annotation tells Java that you’re changing the behavior of the eat method in the Dog class.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> What’s Next?

Tomorrow, we’ll dive into **polymorphism**—a concept that allows objects to act in multiple ways depending on their type. It’s like having a universal remote that can control different devices!

Great job today! You’re mastering some of the coolest features of Java. Keep going—you’re getting closer to being a Java expert! 🚀
