# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a java program to replace each space with a hyphen.

## AIM:
To write a Java program that replaces all spaces in a given string with hyphens (-).

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read a string input from the user.
4.	Use the replace() method to replace all spaces with -.
5.	Display the modified string.
6.	End the program.





## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: JE VARSHA SHARON
RegisterNumber:  212222100058
*/
```

## SOURCE CODE:
```python
import java.util.Scanner;

public class ReplaceSpace {
    public static String replaceSpaces(String str) {
        return str.replace(' ', '-');
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String input = sc.nextLine();
        String result = replaceSpaces(input);
        System.out.println("Modified string: " + result);
    }
}

```




## OUTPUT:
<img width="1145" height="420" alt="image" src="https://github.com/user-attachments/assets/841b12a4-d05c-4d73-831a-22554615c9e4" />



## RESULT:
The program successfully replaces all spaces in the input string with hyphens.

