![image](https://github.com/user-attachments/assets/b47a9f26-3ef7-4b00-81fa-6051901ebc54)# Devops
main
Assignment 1
Assignment | Deepak rao


class Test
{
    public static void main(String[] args)
    {
        System.out.println("My First Java Program.");
    }
}
import java.io.*;

class Devops {
   
    static void Fibonacci(int N)
    {
        int num1 = 0, num2 = 1;

        for (int i = 0; i < N; i++) {
            // Print the number
            System.out.print(num1 + " ");

            // Swap
            int num3 = num2 + num1;
            num1 = num2;
            num2 = num3;
        }
    }

   
    public static void main(String args[])
    {
        // Given Number N
        int N = 10;

        // Function Call
        Fibonacci(N);
    }
}
