Download Link: https://assignmentchef.com/product/solved-csi-3131-assignment-2
<br>









<h1>Question 1</h1>




Write a multithreaded Java, Pthreads, or Win32 program that outputs prime numbers. This program should work as follows: The user will run the program and will enter a number on the command line. The program will then create a separate thread that outputs all the prime numbers less than or equal to the number entered by the user.




<h1>Question 2</h1>




The Fibonacci sequence is the series of numbers 0, 1, 1, 2, 3, 5, 8, …. Formally, it can be expressed as:

<em>fib<sub>0</sub></em> = 0 <em>fib</em><sub>1</sub> = 1

<em>fib<sub>n</sub> </em>= <em>fib<sub>n</sub></em><sub>−1</sub> + <em>fib<sub>n</sub></em><sub>−2</sub>




Write a multithreaded program that generates the Fibonacci series using either the Java, Pthreads, or Win32 thread library. This program should work as follows: The user will enter on the command line the number of Fibonacci numbers that the program is to generate. The program will then create a separate thread that will generate the Fibonacci numbers, placing the sequence in data that is shared by the threads (an array is probably the most convenient data structure).When the thread finishes execution, the parent thread will output the sequence generated by the child thread. Because the parent thread cannot begin outputting the Fibonacci sequence until the child thread finishes, this will require having the parent thread wait for the child thread to finish.