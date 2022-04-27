# Largest-of-three-numbers
## Aim:
  To write a C# program to find the largest of three numbers.

## Algorith:
##Step 1:
To start the C# program in visual Studio 2022.

##Step 2:
Create a class and declare three variable with integer datatype.

##Step 3:
Use if condition to check whether Number1 is largest than number2 and number3.

##Step 4:
Use elif condition to check whether number2 is largest than number1 and number3

##Step 5:
Use else condition to display that third variable is largest among all the variables.

##Step 6:
Finish the C# program and run it.

## Program:
using System;
public class hello
{
    public static void Main()
    {
        int num1, num2, num3;
        Console.WriteLine("Find the largest of three numbers:\n");

        Console.WriteLine("Enter the first number :");
        num1 = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the second number :");
        num2 = Convert.ToInt32(Console.ReadLine());
        Console.WriteLine("Enter the third number :");
        num3 = Convert.ToInt32(Console.ReadLine());

        if (num1 > num2)
        {
            if (num1 > num3)
            {
                Console.WriteLine("The first Number is the greatest among three"+num1);
            }
            else
            {
                Console.WriteLine("The third Number is the greatest among three"+num3);
            }
        }
        else if (num2 > num3)
            Console.WriteLine("The second Number is the greatest among three"+num2);
        else
            Console.WriteLine("The third Number is the greatest among three"+num3);
    }
}


## Output:
![image](https://user-images.githubusercontent.com/75235427/165444231-0a99e286-3104-4924-97a7-11270c561316.png)

## Result:
Thus the C# program to find the largest of three numbers is executed successfully.
