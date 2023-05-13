# Experiment-1

# Arithmetic Operations

## Aim:
  To write a Java program to perform arithmetic operations on the given numbers.
  
## Algorithm

Step 1 : Open Intelli J application or any other code editor.

Step 2 : Create a class and name it ArithmeticOperations.

Step 3 : Using Scanner, we can input numbers from the user.

Step 4 : Write the logic for the program using arithmetic operations.

Step 5 : Display the operations done the input numbers in the terminal.

## Program

```
import java.util.Scanner;
public class ArithmeticOperations
{
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        int b=sc.nextInt();
        int add=a+b;
        int sub=a-b;
        int mul=a*b;
        int div=a/b;
        int rem=a%b;
        System.out.println("Addition of two numbers:"+add);
        System.out.println("Subtraction of two numbers:"+sub);
        System.out.println("Multiplication of two numbers:"+mul);
        System.out.println("Division of two numbers:"+div);
        System.out.println("Remainder of two numbers:"+rem);
    }
}
```


## Output
![1](https://github.com/SaiDarshan2003/Experiment-1/assets/94692595/3dc66244-a8d4-4516-a4e1-942516b7b8ca)

## Result 
  We have successfully created a Java program to display the arithmetic operations on numbers.
