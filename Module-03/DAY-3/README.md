
# Ex.No:3(C)    STRING BUILDER IN JAVA

## AIM:
To Create a java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder

## ALGORITHM :
1.  Start the Program
2.	Import `Scanner` and define class `replace`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read a string `str` from user input
4.	Create a `StringBuilder` object `sb` initialized with `str`
5.	Use the `replace()` method to replace characters from index 1 to 3 with "Java"
6.	Print the modified string using `sb.toString()`
7.	End






## PROGRAM:
 ```
Program to implement a String Builder using Java
Developed by: Arunsamy D
RegisterNumber: 212224240016
```

## Sourcecode.java:

```java
import java.util.Scanner;

public class StringLength {
    public static void main(String[] args) {

        Scanner scanner = new Scanner(System.in);
        String input = scanner.nextLine();

        StringBuilder sb = new StringBuilder(input);

        int length = sb.length();
        System.out.println("The size of the String is " + length);

        scanner.close();
    }
}
```



## OUTPUT:

<img width="732" height="192" alt="439192723-dccc1164-0826-4067-8155-f2ab1f8ab448" src="https://github.com/user-attachments/assets/d03cbe2a-e361-413e-aa52-5e04a148e174" />

## RESULT:
Thus the java program use replace() method replaces the given String from the specified beginIndex and endIndex and use stringbuilder was executed successfully.



