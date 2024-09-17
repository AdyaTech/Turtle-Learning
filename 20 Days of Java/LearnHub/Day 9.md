<div align="center"><h1>Day 9 - Abstract Classes: Blueprints for the Future!</h1></div>

Welcome to Day 9! Today, we’re diving into **abstract classes**—a special type of class that can’t be instantiated on its own but provides a blueprint for other classes. Think of abstract classes as templates that help you create a consistent structure for your classes. Let’s get into it!

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> What is an Abstract Class?

An **abstract class** is a class that cannot be instantiated directly. Instead, it’s meant to be extended by other classes. Abstract classes are used to define common characteristics and behaviors that other classes must implement. They may contain abstract methods, which are methods without a body that must be implemented by subclasses.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> Creating an Abstract Class

Let’s create an abstract class called Shape:

![java banner](https://github.com/AdyaAgr/20-Days-of-Java/blob/main/images/Day%201.png)

**What’s Inside?**

*   **abstract void draw();**: This is an abstract method. It doesn’t have a body and must be implemented by any subclass.
*   **void printName()**: This is a regular method with a body. Subclasses can use or override this method if needed.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> Extending an Abstract Class

Now, let’s create a class that extends the Shape class and provides an implementation for the abstract method:

![java banner](https://github.com/AdyaAgr/20-Days-of-Java/blob/main/images/Day%201.png)

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> What’s Happening?

*   **Circle extends Shape**: This means Circle is a subclass of Shape and must implement the draw method.
*   **@Override void draw()**: Provides the specific implementation of the draw method for Circle and Rectangle.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> Why Use Abstract Classes?

1.  **Define Common Interfaces:** Abstract classes allow you to define common methods and properties that all subclasses must have.
2.  **Prevent Instantiation:** They prevent you from creating objects of a class that isn’t fully defined.
3.  **Promote Reusability:** They help you write reusable code by providing a base for other classes.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> What’s Next?

Tomorrow, we’ll explore **interfaces**—another way to define common methods and behaviors for classes, but with more flexibility and different rules compared to abstract classes.

Great job today! Abstract classes are a powerful tool that helps you set up consistent structures for your classes. Keep up the fantastic work—you’re doing awesome! 🚀
