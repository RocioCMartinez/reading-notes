# Java Imports/Loops/Arrays

In this reading we are trying to gather some more foundational knowledge on the use of import/packages, loops, and arrays. We see how to create a package and are introduced to a 'do-while' loop. We look at the structures of arrays and how they are build in Java.

## Java Imports

1. Use an analogy to explain Built-In packages. Give examples.
2. Explain the steps for creating a new package in IntelliJ.

## Response

1. Built in packages come along with the JDK. In an analogy I would say its like a lunchable, you have items in a box (package) you can access and use to expand on your meal with other ingredients. An example we have used is the java.util to access Random.

2. Creating a package in IntelliJ:

- Find source folder and right-click

- Go to new to access new menu and click package

- A pop-up comes up whree you can set the package name

- Once package is created it will appear in your file system

## Different types of loops in Java

1. Which loop types use a loop counter?
2. Explain the difference between While and Do-While loops

## Responses

1. A for loop.

2. They work in a similar manner except a Do-While loop will consider the condition (boolean) after the first iteration. In a while loop the condition (boolean) is what keeps the iterations happening.

## Java Arrays

1. Describe 3 built-in methods for Arrays.
2. How is the size of an array determined in Java?

## Answers

1. The public static void sort(Object[] a), sorts an array of objects in ascending order.
The public static boolean equals(long[] a, long[] a2), will return true if targeted arrays of longs are equat to each other.
The public static int binarySearch(Object[] a, Object key), searches an array of Object (or other primitive) for a spcific value.

2. In Java you will typically declare the number of elements (or array length) in the array at the moment of creation.

Example:

*"`double[] myList = new double[10];`"*

## Resources

<https://www.programiz.com/java-programming/packages-import>

<https://www.baeldung.com/java-loops>

<https://www.tutorialspoint.com/java/java_arrays.htm>

## Things I want to know more about

I would have to say that I will need more information on building and implementing a package.
