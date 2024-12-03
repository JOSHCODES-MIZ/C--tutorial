# Getting Started with C#

C# (pronounced "C-sharp") is a modern, object-oriented programming language developed by Microsoft. It is commonly used to build Windows applications, web applications, and more.

## Setting Up Your C# Development Environment

1. **Install Visual Studio**: Download and install Visual Studio from [here](https://visualstudio.microsoft.com/downloads/). Visual Studio is an integrated development environment (IDE) that provides all the tools you need to write and run C# programs.
   
2. **Create a Console Application**:
   - Open Visual Studio.
   - Click **Create a new project**.
   - Choose **Console App (.NET Core)** and click **Next**.
   - Name your project (e.g., `HelloWorld`) and click **Create**.

Now you have a basic console application setup and ready to write your first C# program!

## Your First C# Program

In the `Program.cs` file, you will see something like this:

```csharp
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello, World!");
        }
    }
}

