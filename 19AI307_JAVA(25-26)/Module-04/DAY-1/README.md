# Ex.No:4(A) EXCEPTION HANDLING

## QUESTION:
You wrote a program that stores some input strings into a String array and prints each string in uppercase. However, you're getting a NullPointerException. What should you check in your array before calling .toUpperCase() on a element?

## AIM:
To handle a NullPointerException when performing operations on a null string in Java.

## ALGORITHM :
1.	Read a string input from the user.
2.	If the input is "null", assign null to the variable.
3.	Try converting the string to uppercase using toUpperCase().
4.	Catch and handle the NullPointerException if the string is null.
5.	Print "Null element" in case of exception.

## PROGRAM:
 ```
/*
Program to implement a Exception Handling using Java
Developed by: E VARSHA SHARON
RegisterNumber:  212222100058
*/
```

## SOURCE CODE:
```python
import java.util.Scanner;

public class NullPointerArrayExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        String input = sc.next();
        String str = input.equalsIgnoreCase("null") ? null : input;

        try {
            System.out.println(str.toUpperCase());
        } catch (NullPointerException e) {
            System.out.println("Null element");
        }

    }
}
```




## OUTPUT:
<img width="1266" height="354" alt="image" src="https://github.com/user-attachments/assets/ce4117a1-6695-4c6d-a1ca-0cd9f44e94d5" />



## RESULT:
The program successfully detects and handles NullPointerException by displaying "Null element" when the input is null.

