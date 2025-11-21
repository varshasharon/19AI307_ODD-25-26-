# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Define class Game with: Static variable maxScore = 500 Print max score via 3 different object references. Change via one object into 800, and print the output of previous maxScore and changed maxScore. 

## AIM:
To define class Game with: Static variable maxScore = 500 Print max score via 3 different object references. Change via one object into 800, and print the output of previous maxScore and changed maxScore. 

## ALGORITHM :
1.	Start the program.
2.	Import the necessary package 'java.util'
3.	In the main() method, create three objects of Game.
4.	Print maxScore using all three objects.
5.	Modify maxScore to 800 using one object.
6.	Print the updated value using all three objects.
7.	End the program.

## PROGRAM:
 ```
/*
Program to implement a Access Modifiers using Java
Developed by: E VARSHA SHARON
RegisterNumber:  212222100058
*/
```

## SOURCE CODE:
```python
import java.util.*;
class Game 
{
    static int maxScore = 500;
}
public class Main 
{
    public static void main(String[] args)
    {
        Game g1=new Game();
        Game g2=new Game(); 
        Game g3=new Game(); 
        System.out.println(g1.maxScore);
        System.out.println(g2.maxScore); 
        System.out.println(g3.maxScore); 
        g1.maxScore=800;
        System.out.println(g1.maxScore);
        System.out.println(g2.maxScore); 
        System.out.println(g3.maxScore);  
    }
} 
```


## OUTPUT:
<img width="287" height="283" alt="image" src="https://github.com/user-attachments/assets/1c35e3a4-9e6b-4bdc-8371-bcb87e4f52ba" />


## RESULT:
Thus, the Java program demonstrating the use of the static access modifier with multiple object references was successfully executed.

