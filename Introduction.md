Basic Structure of java program:

--> Every valid Java Application must have a class definition that matches the filename (class name and file name should be same).

--> The main method must be inside the class definition. i.e. public static void main(String[] args)

--> The compiler executes the codes starting from the main function.

This is a valid Java program that does nothing.

public class HelloWorld {
    public static void main(String[] args) {
        // Write your code here
    }
}

Java JDK, JRE and JVM :

What is JVM?

JVM (Java Virtual Machine) is an abstract machine that enables your computer to run a Java program.

<img width="776" alt="Screenshot 2023-06-06 at 11 07 26 AM" src="https://github.com/sumshadz/JourneyOfJava/assets/129254642/dbc9fe40-113a-4f60-8a72-2d3bb328ccbe">


Why is Java platform independent?

Java is a platform-independent language. It's because when you write Java code, it's ultimately written for JVM but not your physical machine (computer). Since JVM 
executes the Java bytecode which is platform-independent, Java is platform-independent.

What is JRE?

JRE (Java Runtime Environment) is a software package that provides Java class libraries, Java Virtual Machine (JVM), and other components that are required to run Java applications.
JRE is the superset of JVM.If you need to run Java programs, but not develop them, JRE is what you need.

<img width="413" alt="Screenshot 2023-06-06 at 11 09 53 AM" src="https://github.com/sumshadz/JourneyOfJava/assets/129254642/34ae5216-bd16-40ef-9fcf-18289009d7b7">

What is JDK?

JDK (Java Development Kit) is a software development kit required to develop applications in Java. When you download JDK, JRE is also downloaded with it.

<img width="409" alt="Screenshot 2023-06-06 at 11 11 15 AM" src="https://github.com/sumshadz/JourneyOfJava/assets/129254642/31be8cb1-b475-4b8e-bbc8-66a94ea83f44">

Relationship between JVM, JRE, and JDK:

<img width="422" alt="Screenshot 2023-06-06 at 11 11 40 AM" src="https://github.com/sumshadz/JourneyOfJava/assets/129254642/dd5d96dd-bc38-49af-b717-299e1b29ac9c">

Java Variables:

A variable is a location in memory (storage area) to hold data. To indicate the storage area, each variable should be given a unique name (identifier).

Rules for Naming Variables in Java:

--> Java is case sensitive. Hence, age and AGE are two different variables.

--> Variables must start with either a letter or an underscore, _ or a dollar, $ sign.

--> Variable names cannot start with numbers.

--> Variable names can't use whitespace. 

--> If your variable contains more then one word the use camelCase (i.e. isFeatureEnabled )


