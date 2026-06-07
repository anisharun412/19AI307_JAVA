# Ex.No:3(E)  STRINGBUILDER OBJECT REFERENCE IN JAVA

## AIM:
To write a Java program that creates a StringBuilder object using a given string and assigns its reference to the variable sb.

## ALGORITHM :
1.	Start the program.
2.	Declare and initialize a string variable str1.
3.	Create a StringBuilder object by passing str1 to its constructor.
4.	Store the object reference in the variable sb.
5.	Print the contents of sb to verify the output.
6.	End the program.


## PROGRAM:
 ```
Program to implement a StringBuilder Object Reference in Java
Developed by: Arunsamy D
RegisterNumber: 212224240016
```

## Sourcecode.java:

```java
import java.util.Scanner;

public class StringBuilderExample {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String str1 = scanner.nextLine();

        StringBuilder sb = new StringBuilder(str1);

        System.out.println(sb.length());
        System.out.println( (sb.length() + 16));
    }
}
```





## OUTPUT:
<img width="397" height="308" alt="439196211-5b7a8739-b88f-465d-a187-a0c1f6e35103" src="https://github.com/user-attachments/assets/64329082-71b1-4ff0-9670-199130c740e4" />



## RESULT:
Thus the  Java program successfully creates a StringBuilder object using the given string and stores the reference in the variable sb. The contents of the object are printed using the reference variable.

