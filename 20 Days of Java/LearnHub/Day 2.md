<div align="center"><h1>Day 2 - Variations in Data: The Types Talk!</h1></div>

Welcome back! Today, we’re diving into something super important — **variables** and **data types**. Don’t worry if those words sound a bit fancy. By the end of today, you’ll see just how simple (and fun) they are.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> What are Variables?

Imagine you have a magical box. You can put anything inside this box—like your favorite toy, a number, or even a word. Whenever you need what’s inside, you can just ask the box to give it back to you.

In Java, a **variable** is like that magical box. You use it to store data (like numbers or words) that your program can use later.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> Types of Data (Data Types)

Different kinds of data go in different kinds of boxes. In Java, these “boxes” are called **data types**. Here are some basic ones:

*   **int (integer):** For whole numbers, like 5, 100, or -20.
*   **double:** For numbers with decimals, like 3.14 or 5.0.
*   **char (character):** For single letters or symbols, like ‘A’, ‘b’, or ‘$’.
*   **boolean:** For true or false values, like yes or no.
*   **String:** For words or sentences, like “Hello” or “I love coding!”


<table class="alt"> 
<tbody><tr> 
  <th id="table_dvpt_datatype"><strong>Data Type</strong></th> 
  <th id="table_dvpt_defaultvalue"><strong>Default Value</strong></th> 
  <th id="table_dvpt_defaultsize"><strong>Default size</strong></th> 
</tr> 
<tr> 
<td headers="table_dvpt_datatype">boolean</td> 
<td headers="table_dvpt_defaultvalue">false</td> 
<td headers="table_dvpt_defaultsize">1 bit</td> 
</tr> 
<tr> 
<td headers="table_dvpt_datatype">char</td> 
<td headers="table_dvpt_defaultvalue">'\u0000'</td> 
<td headers="table_dvpt_defaultsize">2 byte</td> 
</tr> 
<tr> 
<td headers="table_dvpt_datatype">byte</td> 
<td headers="table_dvpt_defaultvalue">0</td> 
<td headers="table_dvpt_defaultsize">1 byte</td> 
</tr> 
<tr> 
<td headers="table_dvpt_datatype">short</td> 
<td headers="table_dvpt_defaultvalue">0</td> 
<td headers="table_dvpt_defaultsize">2 byte</td> 
</tr> 
<tr> 
<td headers="table_dvpt_datatype">int</td> 
<td headers="table_dvpt_defaultvalue">0</td> 
<td headers="table_dvpt_defaultsize">4 byte</td> 
</tr> 
<tr> 
<td headers="table_dvpt_datatype">long</td> 
<td headers="table_dvpt_defaultvalue">0L</td> 
<td headers="table_dvpt_defaultsize">8 byte</td> 
</tr> 
<tr> 
<td headers="table_dvpt_datatype">float</td> 
<td headers="table_dvpt_defaultvalue">0.0f</td> 
<td headers="table_dvpt_defaultsize">4 byte</td> 
</tr> 
<tr> 
<td headers="table_dvpt_datatype">double</td> 
<td headers="table_dvpt_defaultvalue">0.0d</td> 
<td headers="table_dvpt_defaultsize">8 byte</td> 
</tr> 
</tbody></table>

NOTE : UTF-8 is the most popular unicode character encoding with 90% websites using it.


## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> Let’s See Some Code!

Let’s create a few variables and see how this works:

![java banner](https://github.com/AdyaAgr/20-Days-of-Java/blob/main/images/Day%202.png)

What just happened? Let’s break it down:

*   **int age = 10;**: We’re telling Java, “I have a box called age, and inside it is the number 10.”
*   **String greeting = "Good morning!";**: Here, we’re storing a sentence inside a String box.

When you run this code, Java will show all the information stored in those variables. You’ll see messages like:

![java banner](https://github.com/AdyaAgr/20-Days-of-Java/blob/main/images/d2a.png)

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> Why Do We Need Variables?

Variables are like memory for your programs. If you want your program to remember a number or a word so it can use it later, you store it in a variable. They’re the backbone of how we make our code smart and interactive.

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> Bonus Tip: Naming Your Variables

When naming your boxes (variables), make it clear what they hold. For example, age is a good name if it stores your age, but x or thing isn’t very helpful.

**Java Naming Conventions:**

<table class="alt">
<tbody><tr><th>Name</th><th>Convention</th></tr>
<tr><td>class name</td><td> should start with uppercase letter and be a noun 
<br>e.g. String, Color, Button, System, Thread etc.</td></tr>
<tr><td>interface name</td><td>should start with uppercase letter and be an adjective 
<br>e.g. Runnable, Remote, ActionListener etc.</td></tr>
<tr><td>method name</td><td>should start with lowercase letter and be a verb 
<br>e.g. actionPerformed(), main(), print(), println() etc.
</td></tr>
<tr><td>variable name</td><td>should start with lowercase letter
<br>e.g. firstName, orderNumber etc.</td></tr>
<tr><td>package name</td><td>should be in lowercase letter 
<br>e.g. java, lang, sql, util etc.
</td></tr>
<tr><td>constants name</td><td>should be in uppercase letter.
<br>e.g. RED, YELLOW, MAX_PRIORITY etc.</td></tr>
</tbody></table>

## <img src = "https://cdn0.iconfinder.com/data/icons/huge-basic-icons-part-3/512/Java.png" align = "left" width = "30"> What’s Next?

Tomorrow, we’ll play with **operators**—they let us add, subtract, compare, and do other cool tricks with our variables. Get ready for some math magic!

That’s a wrap for today! Now you know how to make Java remember things for you. Keep practicing - every little step counts! 🚀
