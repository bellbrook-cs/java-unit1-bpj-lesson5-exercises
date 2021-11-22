# Lesson 5 Exercises

Unless otherwise instructed in the following problems, state what gets printed.

1. Write code that will create a constant `E` that’s equal to `2.718`.  
2. Write the simplest type constant that sets the number of students, `NUM_STUDENTS`, to `236`.  
3. What’s wrong, if anything, with the following code in the `main` method? 

```java
final double Area; 
Area = 203.49;  
```

4. 

```java
int cnt = 27.2;  
System.out.println(cnt);  
```

What’s printed?  

5. 

```java
double d = 78.1;  
int fg = (int)d; 
System.out.println(fg);  
```

What’s printed?  

6. Is `double f4 = 22;` legal?  
7. The following code stores a `20` in the variable `j`:  

```java
double j = 61/3;  
```

What small change can you make to this single line of code to make it produce the "real" answer to the division?  

8. 

```java
System.out.println( (double)(90/9) );
```   

9. 

```java
System.out.println(4 + 6.0/4 + 5 * 3 – 3); 
```

10. 

```java
int p = 3;  
double d = 10.3;  
int j = (int)5.9;  
System.out.println(p + p * d – 3 * j);  
```

11. 

```java
int p = 3;  
double d = 10.3;  
int j = (int)5.9;  
System.out.println(p + p * (int)d – 3 * j);  
```


The following code applies to 12 – 15: 

```java
int dividend = 12, divisor = 4, quotient = 0, remainder = 0;  
int dividend2 = 13, divisor2 = 3, quotient2 = 0, remainder2 = 0;  
quotient = dividend/divisor;  
remainder = dividend % divisor;  
quotient2 = dividend2 / divisor2;  
remainder2 = dividend2 % divisor2;  
```

12. `System.out.println(quotient);`  
13. `System.out.println(remainder);` 
14. `System.out.println(quotient2);`  
15. `System.out.println(remainder2);`  
16. Write a line of code in which you divide the `double` precision number `d` by an integer variable called `i`. Type cast the `double` so that strictly integer division is done. Store the result in `j`, an integer.  
17. Suppose we have a line of code that says  

```java
final String M = "ugg"; 
```

Later in the same program, would it be permissible to say the following?  `M = "wow";` 

18. Is the following code legal? If so, what is printed? If not, why?  

```java
int k = 7;  
k*=.5;  
System.out.println(k);
```
