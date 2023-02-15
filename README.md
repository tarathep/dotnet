# dotnet

## Create a .NET console application using CLI

Create the App

```ps
dotnet new console --framework net7.0
```
Run the App

```ps
dotnet run
```

Replace the contents of Program.cs with the following code:

```c#
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
```