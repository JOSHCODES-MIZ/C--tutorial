# Basic Math Operations in C# 
In this tutorial, we will cover the basic math operations that you can perform in C#. These operations include addition, subtraction, multiplication, and division. 
## _Addition_

To perform addition, you simply use the `+` operator. 

 using System;
 
namespace BasicMathOperations
  {
   class Program
  {
   static void Main(string[] args)
{ 
int num1 = 10;
int num2 = 5;
int result = num1 + num2;
Console.WriteLine("Addition: " + num1 + " + " + num2 + " = " + result);
         }
     }
}

Output: 10 + 5 = 15

##_Subtraction_

To perform subtraction, you use the - operator.

csharp

using System;

namespace BasicMathOperations
{
    class Program
    {
        static void Main(string[] args)
        {
            int num1 = 10;
            int num2 = 5;
            int result = num1 - num2;

            Console.WriteLine("Subtraction: " + num1 + " - " + num2 + " = " + result);
        }
    }
}


Subtraction: 10 - 5 = 5

##_Multiplication_

To perform multiplication, you use the * operator.


using System;

namespace BasicMathOperations
{
    class Program
    {
        static void Main(string[] args)
        {
            int num1 = 10;
            int num2 = 5;
            int result = num1 * num2;

            Console.WriteLine("Multiplication: " + num1 + " * " + num2 + " = " + result);
        }
    }
}

Multiplication: 10 * 5 = 50

##Division
To perform division, you use the / operator. Be careful with division by zero, as this will cause an error.

using System;

namespace BasicMathOperations
{
    class Program
    {
        static void Main(string[] args)
        {
            int num1 = 10;
            int num2 = 5;
            int result = num1 / num2;

            Console.WriteLine("Division: " + num1 + " / " + num2 + " = " + result);
        }
    }
}

Division: 10 / 5 = 2

In summary these are basic C# Math Operations. You can try them yourself and make them even more comnplex to challenge yourself! Goodluck!
