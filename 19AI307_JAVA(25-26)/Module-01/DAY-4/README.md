# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to print all elements in an array that are greater than a given value

## AIM:
To write a Java program that prints all elements in an array greater than a given value.

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	Read the size n and elements of the array.
4.	Read a value to compare with.
5.	Use a loop to check and print elements greater than the given value.
6.	End the program.





## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: E VARSHA SHARON
RegisterNumber:  212222100058
*/
```

## SOURCE CODE:
```python
import java.util.Scanner;

public class ElementsGreaterThanX {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        int n = scanner.nextInt();     // size of array
        int[] arr = new int[n];

        for(int i = 0; i < n; i++) {
            arr[i] = scanner.nextInt();  // array elements
        }

        int x = scanner.nextInt();     // value to compare

        boolean found = false;

        for(int i = 0; i < n; i++) {
            if(arr[i] > x) {
                System.out.println(arr[i]);
                found = true;
            }
        }

        if(!found) {
            System.out.println("No elements greater than " + x);
        }
    }
}

```




## OUTPUT:
<img width="1141" height="823" alt="image" src="https://github.com/user-attachments/assets/60d1722f-f32c-4ba3-bdc4-a740bbace4c7" />



## RESULT:
The program successfully prints all array elements greater than the given value.

