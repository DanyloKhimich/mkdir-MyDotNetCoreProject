git add .

git commit -m "Initial commit with .NET Core console project"
git feature/add-greeting
using System;

 

class Program

{

    static void Main(string[] args)

    {

        Console.WriteLine("Hello, World!");

        GreetUser("DANYLO");

    }

 

    static void GreetUser(string name)

    {

        Console.WriteLine("Hello, {DANYLO}!");

    }
git add Program.cs

git commit -m "Add GreetUser function to Program.cs"
}
}
