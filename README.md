# OOP-Java
This project is a comprehensive exploration of Object-Oriented Programming (OOP) principles using Java.









# Table of Contents

  - [1. Introduction to Object-Oriented Programming](#1-introduction-to-object-oriented-programming)
  Introduction to Java
  Writing My First Program in Java
  Java Operators
  - [2. Core Java Concepts](#2-core-java-concepts)

  - [3. Advanced Java Features](#3-advanced-java-features)
  - [4. Design Patterns in Java](#4-design-patterns-in-java)
  - [5. Java and Database Connectivity](#5-java-and-database-connectivity)
  - [6. Testing in Java](#6-testing-in-java)
  - [7. Java Project Examples](#7-java-project-examples)
  - [8. Additional Resources and References](#8-additional-resources-and-references)


## Prequisites

- Here in this repository I won't talk about the basics of programming. I assume that you have a basic understanding of programming concepts like variables, loops, functions, etc. If you are new to programming, I recommend you to go through the following instruction before starting with this repository.

You can check out my <a href="https://github.com/saky-semicolon/Introduction-to-Programming"> <strong>Introduction to Programming </strong></a> repository for a quick overview of programming concepts.

## 1. Introduction to Object-Oriented Programming


Object-Oriented Programming (OOP) is a programming paradigm that revolves around the concept of "objects," which can contain data in the form of fields (attributes or properties) and code in the form of procedures (methods or functions). It's a way of structuring software by modeling real-world entities as objects that interact with each other.

OOP languages, such as Java, C++, Python, and others, enable developers to create modular, reusable, and maintainable code by organizing it into objects that interact with each other. It provides a way to manage complexity in software development by breaking down problems into manageable entities (objects) that model real-world or abstract concepts.

History
Simula: 
	First OOP, Developed at 1960s by Ole Johan Dahl

Smalltalk: 
	First purely OOP, at 1970s by Xerox

C++: 
	C language with additional features, widely used for developing system 	and application software, 

JAVA: 
	Its similar to C++ that eliminates lots of C++’s problematic features, 	Allow to develop a web base application


James Gosling initiated Java language project in June 1991 for use in one of his many set-top box projects. 


The language, initially called ‘Oak’ after an oak tree that stood outside Gosling's office, also went by the name ‘Green’ and ended up later being renamed as Java, from a list of random words.

Sun released the first public implementation as Java 1.0 in 1995.

It promised Write Once, Run Anywhere (WORA), providing no-cost run-times on popular platforms.

On 13 November, 2006, Sun released much of Java as free and open source software under the terms of the GNU General Public License (GPL).

On 8 May, 2007, Sun finished the process, making all of Java's core code free and open-source, aside from a small portion of code to which Sun did not hold the copyright.

In 1991, later acquired by Oracle Corporation


## Introduction to Java

High-level, Third generation programming language, and Object Oriented language.

Java has its own structure, syntax rules, and programming paradigm based on the concept of OOP

The Java language is a C-language derivative, so its syntax rules look much like C++

Easier to write bug free code

1. Main Features of Java
Platform independent language
 Compiler (javac) converts source code (.java file) to the byte code (.class file)
 JVM executes the byte code
 Byte code can run on any platform such as Windows, Linux, Mac OS etc
 Each operating system has different JVM, however the output they produce after 	execution of byte code is same across all operating systems. 
 That is why we call java as platform independent language.
 Byte codes can be run on any machine by an interpreter called the Java Virtual Machine (JVM) and thus java provides ‘reusability of code’.
 
Object Oriented programming language: 
 OOP makes the complete program simpler by dividing it into a number of objects
 Objects can be used as a bridge to have data flow from one function to another
 Easily modify data and function as per the requirements of the program
 Abstraction, Encapsulation, Inheritance, Polymorphism are main concepts of OOPs
 C++ is the partialy OOP and Java is the fully OOP.

Simple: 
Java is easy to learn and its syntax is clear and concise based on C++
Removed many confusing 
Takes care of memory management
Provides an automatic garbage collector
Collect the unused objects automatically.
  
Robust language: 
Robust means reliable or strong
Less crash means strong. “Sorry, not able to run” this error message
Resolve the Memory management mistake
Handle the exceptional conditions

Garbage collection
	Developed in a way that puts a lot of importance on early checking for possible errors, 	that’s why java compiler is able to detect errors that are not easy to detect in other 	programming languages. 
	Makes it robust are garbage collection, Exception Handling and memory allocation

Secure
Don’t have pointers
Cannot access outofbound arrays( you get ArrayIndexOutOfBounds
Exception if you try to do so) in java. 
Several security flaws like stack corruption or buffer overflow is impossible in Java.

Distributed
Can be distributed on more than one systems that are connected to each other using internet connection.
Objects on one JVM can execute procedures on a remote JVM.
RMI (Remote Method Invocation) and EJB (Enterprise Java Beans) are used for creating distributed applications. 

Multithreading
Perform many tasks at once by defining multiple threads
Allows concurrent execution of two or more parts of a program for maximum utilization of CPU 
Example:  A program that manages a Graphical User Interface (GUI) while waiting for input from a network connection uses another thread to perform and wait’s instead of using the default GUI thread for both tasks. This keeps the GUI responsive. 

Portable
Java code is written on one machine can run on another machine, that means byte code can be carried to any platform for execution 
Dynamic  and Java is considered to be more dynamic than C or C++  

High Performance
With the use of Just-In-Time compilers, Java enables high performance.
not require any pre processor: 
not require inclusion of header files for creating a Java application 

Interpreted 
Java byte code is translated on the fly to native machine  

Create applets
Applets are programs that run in web browsers.

2. Types of Java Application

Standalone Application
Standalone applications are also known as desktop applications or window-based applications. 

These are traditional software that we need to install on every machine. 

Examples: Media player, antivirus, etc. AWT and Swing are used in Java for creating standalone applications.


 Web Application
An application that runs on the server side and creates a dynamic page is called a web application. 

Example : Servlet, JSP, Struts, Spring, Hibernate, JSF, etc. 

Enterprise Application
An application that is distributed in nature, such as banking applications, etc. is called enterprise application. 

It has advantages of the high-level security, load balancing, and clustering. 

In Java, EJB is used for creating enterprise applications.


 Mobile Application
An application which is created for mobile devices is called a mobile application.

Currently, Android and Java ME are used for creating mobile applications.

3. Phases of Java Program Execution

Writing of the Java program in any editor

Compilation of program is done by javac compiler
javac is the primary java compiler included in java development kit (JDK). 
It takes java program as input and generates java bytecode as output.

JVM executes the bytecode generated by compiler. This is called program run phase.

PHOTOS ABOUT THE EXECUTION PROCEDURE

3. Java Development Kit (JDK)
A Java distribution typically comes in two flavors
Java Runtime Environment (JRE) 
Java Development Kit (JDK)

JDK provides environment and tools for developing, compiling, debugging, and executing a Java program.

Core components of JDK include
	JRE (Java Runtime Environment), Java Compiler, Development Tools 	(ex:JavaDoc, Java debugger etc.)


Some tools:
javac – reads class and interface definitions and compiles them into class files

java – launches the Java application

javadoc – generates HTML pages of API documentation from Java source files

apt – finds and executes annotation processors based on the annotations present in the set of specified source files

appletviewer – enables us to run Java applets without a web browser

jar – packages Java applets or applications into a single archive

jdb – a command-line debugging tool used to find and fix bugs in Java applications


5. Java Runtime Environment (JRE)

The JRE is included in the JDK.

It is a bundle of software components used to run Java applications.

Core components of the JRE include:
An implementation of a Java Virtual Machine (JVM)
Java Class libraries required to run the Java programs
Property Files

Some Core classes and support files
Bootstrap Classes : We’ll find bootstrap classes under jre/lib/.  This path is also known as the bootstrap classpath. 
It includes: Runtime classes in rt.jar, Internationalization classes in i18n.jar, Character  conversion classes in charsets.jar

Bootstrap ClassLoader loads these classes when the JVM starts up.

6. Java Virtual Machiene

The JVM is the heart of the Java language’s “write-once, run-anywhere (WORA)” principle.  

Its an implementation of a virtual machine which executes a Java program.

The JVM first interprets the bytecode. 

It then stores the class information in the memory area. 

Finally, it executes the bytecode generated by the java compiler.

It is an abstract computing machine with its own instruction set and manipulates various memory areas at runtime.

Each operating system has different JVM . e.g., for Linux a special implementation is required as well as for Windows

 However the output they produce after execution of byte code is same across all operating systems. That is why we call java as platform independent language.


.class file is create as the result of .java execution 

.class file give the Input to JVM

JVM is the responsible for load and execute the .class file

When you call java .class file , at that time JVM instance  will be create

Byte code will be loaded some storage area or memory area. So Actual JVM architecture involve one more component which call as memory areas.

So JVM architecture  break down as a three main component

7. Difference among JDK, JRE, JVM

JDK is for development purpose whereas JRE is for running the java programs.

JDK and JRE both contains JVM so that we can run our java program.

JVM is the heart of java programming language and provides platform independence.


8. Software Development Process in Java

In the Java programming language, all source code is first written in plain text files ending with the .java extension.
Creating a Java Source File : Using Notepad(Windows)/Gedit(Linux) editor enter the following program. 
		class MyProgram {  public static void main(String[] args)  {  
				System.out.println("Hello World!"); //Display the string. }}
Save the file as MyProgram.java
Compiling the Source file javac MyProgram.java
If the compilation succeeds, the compiler creates a file named MyProgram.class in the same directory (folder) as the Java source file (MyProgram.java). 
A .class file does not contain code that is native to your processor; it instead contains byte codes
Run the Application java MyProgram
You should see "Hello World!" displayed.


## Writing My First Program in Java

1. How to run java program?





2. First Program in Java

class HelloWorld 
{ 
	public static void main (String[] args)
	{ 
	System.out.println (“Hello World!!!”); 
	} 
}

3. Public Static Void Main (String[] args)

public: 
    access modifier, which allows the programmer to control the visibility of class members. 
    When a class member is preceded by public, then that member may be accessed by code outside the class in which it is declared. 
    When no access modifier is specified for a class member, then the default access modifier is used.

class: 
    keyword used to declare a class in Java. 
    In our example, we have declared a class named HelloWorld. 
    Classes are the basic units of programming in the object-oriented paradigm.

    Class : Bike    ,      Important Method/Activity : Key Insertion, 	Activities (Method/ Function)  : Running Speed meter, fill 								petrol, wheel rotator, Sit the seat, 

Class : College    ,      Important Method/Activity : Main Gate Opening,	Activities (Method/ Function) :  Lab, Auditorium, 									Class, Canteen 

Class : Home    ,      Important Method/Activity :Main Meter On/Off,	Activities (Method/ Function)  :  Switch Board, 									Tube light switch, AC switch, Fan switch

Static:
Static – Keyword of Java and C#   	Static – Permanent

Object – Combination of state and Behavior (Method) / real time entity

Class can also have state and behavior

Example : Bike – Scooty    Name – Scooty   (This is the behavior of class), Color – Red  

Engine CC match with Engine, No.Of Gear match with Gear, Maximum KM Match With Speed meter.  But these object not match with Class (Scooty)

Red color not match with any object. It match with Class

Example  : Human (  Nationality, name, Mother toque which are not match with Object)
Not match with Object called as static
Static member (State/Behavior/ variable/ method)  are common to all the object
Static member are associate with class, rather than with any object
Static refer class level
So I don’t want any object for execute the main method

Main:

The Main method in Java is an standard method which is used by JVM to start execution of any Java program.
A main method declaration looks as follows:
		public static void main(String args[]){
		}
The method is public because it be accessible to the JVM to begin execution of the program.


## Core Java Concepts

1. Java Identifiers
All Java components require names. Names used for classes, variables and methods are called identifiers. 
All identifiers should begin with a letter A to Z or a to z, currency character $ or an underscore _ . 
After the first character identifiers can have any combination of characters. 
A key word cannot be used as an identifier. 
Most importantly identifiers are case sensitive. 
Examples of legal identifiers: age, $salary, _value, __1_value 
Examples of illegal identifiers: 123abc, -salary 

2. Java Keyworsds

abstract 
assert 
boolean 
break 
byte 
case 
catch 
char 
class 
const 
continue 
default 
do 
double
else 
enum 
extends 
final 
finally 
float 
for 
goto 
if 
implements 
import 
instanceof 
Int
interface 
long 
native 
new 
package 
private 
protected 
public 
return 
short 
static 
strictfp 
super
switch 
synchronized 
this 
throw
throws 
transient 
try 
void 
volatile 
while

3. Structure of Java Program
A java application can be consists followings.
Class
Object
Package 
Interface

4. Class

Java is the fully pure class-oriented language

Classes is a User define data type

Classes have collection of variable and method(function)
		OR Collection of Object

Defined by the class keyword. body of a class is surrounded by {}.

Class member is accessed only by object

It is also possible to define inner classes, 
   these are classes defined within another class.
Do not need a separate file for inner class.

Bus is the imagination, because created by us. Not real. So define the limitation areas { }
One activity (method) is main activity in the class (power on in laptop, main switch in home, etc.). SO in general, no result without main method. In Java said, main method of that main activity
Main method comes under the class. ( ex :  key insert in motorbike, power on button in laptop). 
Is main method spread all class or part of the class. Absolutely it’s a part of class . But main method has the control of all class (Ex: without power button nothing work. But power button in one place)

5. Object
Object is defined as 
Real time entity
Combination of state and behavior
An entity that contain data and its related function
Object is a representation of Class
An object is an instance of a class.

Actual real-world entities are represented by objects. Objects are instances of classes.

The object is the real element which has data and can perform actions.

Each object is created based on the class definition.

is the class created by system memory or actual class ? (Ex: bus class creating is the allocation the memory to bus.
I can park a bike in this lab. But not car. Because of space. So if I bring the object inside the class, need the space. 
If real class ,  need the real space. Now we are creating the object in the memory. So we need to create the space in memory to the object.
Every object we need to create memory separately. That means uniquely. So called NEW as a keywork in computer

6. Attributes and Methods

Real world entities have various characteristic attributes. 
For example, a Person has a name, age, gender etc.

Real world entities have characteristic behaviors. 
For example, a Person may Walk, Talk, Sleep etc.

Similarly, Objects in java also have attributes and perform methods. These are defined in the classes.

7. Inside of a Class

Methods  
A method is a set of code which is referred to by name and can be called (invoked) at any point in a program simply by utilizing the method's name. 

Method is a subprogram that acts on data and often returns a value. 

Each method has its own name.

Instance Variables 
Variables are devices that are used to store data, such as a number, or a string of character data.

8. Statements and Expressions
Statements 
A method is made up of statements.
A statement is a simple command written in a programming  language that causes something to happen.
For example,
 	System.out.println (“Hello World!!!”);
		It prints “Hello World!!!”on the command line.
In Java, we denote the end of a statement with a semicolon “;”. 

Expressions 
“expression” in Java is a segment of code that can be evaluated to give a value. 
An expression is a combination of Variables, Literals, Operators and Functions (methods that return values).
Expressions can be combined to give more complex expressions.

9. Literals
Any constant value which can be assigned to the variable is called as literal/constant.
Literals can be assigned to any primitive type variable.
Example
	byte a = 68; char a = 'A'

A literal is a source code representation of a fixed value. They are represented directly in the code without any computation.
Literals can be assigned to any primitive type variable.

In Java, we have four types of literals 
Number Literals (Integers and Real Numbers)  
For example, 2004, 3.1416 
Boolean Literals (Logical True and False) 
For example, true, false 
Character Literals (A single character) 
For example, ‘1’, ‘a’ 
String Literals (A sequence or string of characters) 
For example, “Hello World!!!”, “CTGU”

10. Variables and Data Types

Variables are locations in memory in which values can be stored.
Each Variable has a Data Type, Name and a Value.
A variable’s Data Type defines what type of data and what size of the data, it can store. 
A variable’s Value is the data that it is currently storing.

Before use, variables should be Declared. That is, we specify that the variable with this particular name will store data of this particular type

Variable declarations take the form: 
VariableType VariableName 
For example: 
int x; 
char a;
Variables of the same type may be declared on the same line 
For example,
 int x, y, z;



## Java Operators

An operator is a function that has a special symbolic name and is invoked by using that symbol with an expression.
Operator help to perform action between two operands
Java has several kinds of operators. Op1 <Operator> Op2

1. Arithmetic Operator

| Operator | Description | Example |
|----------|-------------|---------|
| +        | Addition    | 5 + 3   |
| -        | Subtraction | 8 - 2   |
| *        | Multiplication | 4 * 6 |
| /        | Division    | 10 / 2  |
| %        | Modulus (remainder) | 7 % 3 |

    public class ArithmeticOperatorsExample {
        public static void main(String[] args) {
            int num1 = 5;
            int num2 = 3;

            // Addition
            int sum = num1 + num2;
            System.out.println("Sum: " + sum);

            // Subtraction
            int difference = num1 - num2;
            System.out.println("Difference: " + difference);

            // Multiplication
            int product = num1 * num2;
            System.out.println("Product: " + product);

            // Division
            int quotient = num1 / num2;
            System.out.println("Quotient: " + quotient);

            // Modulus
            int remainder = num1 % num2;
            System.out.println("Remainder: " + remainder);
        }
    }


2. Relational Operator

| Operator | Description | Example |
|----------|-------------|---------|
| ==       | Equal to    | 5 == 5  |
| !=       | Not equal to | 6 != 3 |
| >        | Greater than | 8 > 2   |
| <        | Less than   | 4 < 6   |
| >=       | Greater than or equal to | 10 >= 5 |
| <=       | Less than or equal to    | 7 <= 9  |

    public class RelationalOperatorsExample {
        public static void main(String[] args) {
            int a = 5;
            int b = 10;

            // Equal to
            boolean isEqual = (a == b);
            System.out.println("a == b: " + isEqual);

            // Not equal to
            boolean isNotEqual = (a != b);
            System.out.println("a != b: " + isNotEqual);

            // Greater than
            boolean isGreaterThan = (a > b);
            System.out.println("a > b: " + isGreaterThan);

            // Less than
            boolean isLessThan = (a < b);
            System.out.println("a < b: " + isLessThan);

            // Greater than or equal to
            boolean isGreaterThanOrEqual = (a >= b);
            System.out.println("a >= b: " + isGreaterThanOrEqual);

            // Less than or equal to
            boolean isLessThanOrEqual = (a <= b);
            System.out.println("a <= b: " + isLessThanOrEqual);
        }
    }


3. Bitwise Operator

| Operator | Description | Example |
|----------|-------------|---------|
| &        | Bitwise AND | 5 & 3   |
| \|       | Bitwise OR  | 5 \| 3  |
| ^        | Bitwise XOR | 5 ^ 3   |
| ~        | Bitwise NOT | ~5      |
| <<       | Left shift  | 5 << 2  |
| >>       | Right shift | 5 >> 2  |
| >>>      | Unsigned right shift | 5 >>> 2 |

    public class BitwiseOperatorsExample {
        public static void main(String[] args) {
            int a = 5; // 101
            int b = 3; // 011

            // Bitwise AND
            int bitwiseAnd = a & b; // 001
            System.out.println("a & b: " + bitwiseAnd);

            // Bitwise OR
            int bitwiseOr = a | b; // 111
            System.out.println("a | b: " + bitwiseOr);

            // Bitwise XOR
            int bitwiseXor = a ^ b; // 110
            System.out.println("a ^ b: " + bitwiseXor);

            // Bitwise NOT
            int bitwiseNot = ~a; // 010
            System.out.println("~a: " + bitwiseNot);

            // Left shift
            int leftShift = a << 2; // 10100
            System.out.println("a << 2: " + leftShift);

            // Right shift
            int rightShift = a >> 2; // 001
            System.out.println("a >> 2: " + rightShift);

            // Unsigned right shift
            int unsignedRightShift = a >>> 2; // 001
            System.out.println("a >>> 2: " + unsignedRightShift);
        }
    }

4. Logical Operator

Logical operators in Java are used to perform logical operations on boolean values. They evaluate the truth or falsity of a given expression and return a boolean result.

| Operator | Description | Example |
|----------|-------------|---------|
| &&       | Logical AND | true && false |
| \|\|      | Logical OR  | true \|\| false |
| !        | Logical NOT | !true      |

The logical AND operator (`&&`) returns `true` if both operands are `true`, otherwise it returns `false`.

The logical OR operator (`||`) returns `true` if at least one of the operands is `true`, otherwise it returns `false`.

The logical NOT operator (`!`) negates the value of the operand. If the operand is `true`, it returns `false`, and if the operand is `false`, it returns `true`.

Note: Short-circuit evaluation is used for logical operators. This means that if the result of the expression can be determined by evaluating only the first operand, the second operand is not evaluated.

    public class LogicalOperatorsExample {
        public static void main(String[] args) {
            boolean a = true;
            boolean b = false;

            // Logical AND
            boolean logicalAnd = a && b;
            System.out.println("a && b: " + logicalAnd);

            // Logical OR
            boolean logicalOr = a || b;
            System.out.println("a || b: " + logicalOr);

            // Logical NOT
            boolean logicalNot = !a;
            System.out.println("!a: " + logicalNot);
        }
    }

5. Assignment Operator

The assignment operator in Java is used to assign a value to a variable. It is denoted by the symbol `=`.

| Operator | Description | Example |
|----------|-------------|---------|
| =        | Assigns the value on the right to the variable on the left | int x = 5; |

The assignment operator can also be combined with other operators to perform compound assignments. Here are some examples:

| Operator | Description | Example |
|----------|-------------|---------|
| +=       | Adds the value on the right to the variable on the left and assigns the result to the variable on the left | x += 3; // equivalent to x = x + 3; |
| -=       | Subtracts the value on the right from the variable on the left and assigns the result to the variable on the left | x -= 2; // equivalent to x = x - 2; |
| *=       | Multiplies the value on the right with the variable on the left and assigns the result to the variable on the left | x *= 4; // equivalent to x = x * 4; |
| /=       | Divides the variable on the left by the value on the right and assigns the result to the variable on the left | x /= 2; // equivalent to x = x / 2; |
| %=       | Computes the remainder of dividing the variable on the left by the value on the right and assigns the result to the variable on the left | x %= 3; // equivalent to x = x % 3; |

Note: The compound assignment operators are shorthand notations for performing arithmetic operations and assigning the result back to the variable.
    
        public class AssignmentOperatorsExample {
            public static void main(String[] args) {
                int x = 5;
    
                // Simple assignment
                x = 5;
                System.out.println("x = " + x);
    
                // Add and assign
                x += 3; // equivalent to x = x + 3;
                System.out.println("x += 3: " + x);
    
                // Subtract and assign
                x -= 2; // equivalent to x = x - 2;
                System.out.println("x -= 2: " + x);
    
                // Multiply and assign
                x *= 4; // equivalent to x = x * 4;
                System.out.println("x *= 4: " + x);
    
                // Divide and assign
                x /= 2; // equivalent to x = x / 2;
                System.out.println("x /= 2: " + x);
    
                // Modulus and assign
                x %= 3; // equivalent to x = x % 3;
                System.out.println("x %= 3: " + x);
            }
        }

6. Conditional Operators / Misc

Conditional Operator (?:)
This operator has the form: 
(condition)?(valueif true):(valueif false) 
The condition is evaluated and if it is true value if true is returned, otherwise value if false is returned.
For example, if a and b were integers, the following would return the maximum of a and b. 
(a>b)?a:b
This is a short hand for “if-then-else”

    public class ConditionalOperatorExample {
        public static void main(String[] args) {
            int a = 10;
            int b = 20;

            int max = (a > b) ? a : b;
            System.out.println("The maximum value is: " + max);
        }
    }


7. Unary

| Operator | Description |
|----------|-------------|
| ++       | Increment the value by 1 |
| --       | Decrement the value by 1 |
| +        | Unary plus (no effect on the value) |
| -        | Unary minus (negates the value) |
| !        | Logical NOT (negates the boolean value) |

    public class UnaryOperatorExample {
        public static void main(String[] args) {
            int x = 5;

            // Increment
            x++;
            System.out.println("x after increment: " + x);

            // Decrement
            x--;
            System.out.println("x after decrement: " + x);

            // Unary plus
            int y = +x;
            System.out.println("y after unary plus: " + y);

            // Unary minus
            int z = -x;
            System.out.println("z after unary minus: " + z);

            // Logical NOT
            boolean logicalNot = true;
            boolean result = !logicalNot;
            System.out.println("result of logical NOT: " + result);
        }
    }









<!-- 



3. Advanced Java Features
    3.1. Generics
    3.2. Multithreading
    3.3. File Handling and I/O
    3.4. Java GUI (Swing or JavaFX)
    3.5. Networking in Java

4. Design Patterns in Java
    4.1. Creational Patterns
    4.2. Structural Patterns
    4.3. Behavioral Patterns

5. Java and Database Connectivity
    5.1. JDBC Basics
    5.2. Connecting Java with MySQL/Oracle/other databases
    5.3. CRUD Operations

6. Testing in Java
    6.1. JUnit Testing
    6.2. Test-Driven Development (TDD)
    6.3. Integration Testing

7. Java Project Examples
    7.1. Simple Java Applications
    7.2. Mini Projects
    7.3. Larger Projects showcasing multiple concepts

8. Additional Resources and References
    8.1. Recommended Books
    8.2. Online Tutorials and Courses
    8.3. Useful Java Libraries and Frameworks
 -->






