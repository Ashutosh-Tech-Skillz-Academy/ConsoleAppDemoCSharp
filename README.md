# ConsoleAppDemoCSharp
1. Console Application with and without Top Level Statements
Discussion and Demo
1.1 Without Top Level Statements
dotnet new console -o demo1 --use-program-main
Demo 1 |150x150

1.2. With Top Level Statements
Top level Statements, will create Program class, and <Main>$() method
dotnet new console -o demo2
using System;
using System.Runtime.CompilerServices;

[CompilerGenerated]
internal class Program
{
    private static void <Main>$(string[] args)
    {
        Console.WriteLine("Hello, World!");
    }
}
Demo 2 |150x150

2. Creating a Console Application within an Existing and New folder
Discussion and Demo
2.1. Creating a Console Application within an Existing folder
Create a folder existingfolder
Open cmd and navigate to existingfolder
Run the below command
This will create a console application within the existingfolder
It will name the console application as existingfolder
dotnet new console
dotnet new console -n "projectName" .
Existing folder Demo |150x150

2.2. Creating a Console Application within a New folder
Execute the below command
This will create a console application within the newfolder
It will name the console application as newfolder
dotnet new console -o newfolder
dotnet new console -n "projectName"
dotnet new console -n "projectName" -o folderName
New folder Demo |150x150

3. Viewing Compiler Version and Language Version
Discussion and Demo
Compiler Version |150x150

4. Creating a Console Application with different .NET (6/7/8)
Discussion and Demo
4.1. Creating a Console Application with different .NET 6
dotnet new console -o demo3 -f net6.0
Demo 3 |150x150

4.2. Creating a Console Application with different .NET 7
dotnet new console -o demo4 -f net7.0
Demo 4 |150x150

4.3. Creating a Console Application with different .NET 8
dotnet new console -o demo5 -f net8.0
Demo 5 |150x150

5. Creating a Console Application with global.json inside folder
Discussion and Demo
Execute the below command
dotnet new list

dotnet new globaljson --help

dotnet --list-sdks

dotnet new globaljson --sdk-version <VersionNumber> --dry-run
dotnet new globaljson --sdk-version <VersionNumber>
Global JSON |150x150

5.1. Creating a Console Application with different .NET 6
dotnet --list-sdks

dotnet new globaljson --sdk-version 6.0.408 --dry-run
dotnet new globaljson --sdk-version 6.0.408

dotnet new console -o demo6
Global JSON .NET 6 |150x150

5.2. Creating a Console Application with different .NET 7
dotnet --list-sdks

dotnet new globaljson --sdk-version 7.0.105 --dry-run
dotnet new globaljson --sdk-version 7.0.105

dotnet new console -o demo7
Global JSON .NET 7 |150x150

5.3. Creating a Console Application with different .NET 8
dotnet --list-sdks

dotnet new globaljson --sdk-version 8.0.100-preview.4.23260.5 --dry-run
dotnet new globaljson --sdk-version 8.0.100-preview.4.23260.5

dotnet new console -o demo8
Global JSON .NET 8 |150x150

6. Executing the Same Application in .NET 6/7/8
Discussion and Demo
Copy and paste the below code in Program.cs file in 6/7/8 projects
Execute the project in 6/7/8
View the output
6.1. Sample C# Code
// See https:// aka.ms/ new-console-template for more information
Console.WriteLine(Environment.CurrentDirectory);
Console.WriteLine(Environment.OSVersion.VersionString);
Console.WriteLine(Environment.Version);
Console.WriteLine(Environment.UserName);
Console.WriteLine(Environment.MachineName);
Console.WriteLine(Environment.ProcessorCount);
Console.WriteLine(Environment.SystemDirectory);
Console.WriteLine(Environment.UserDomainName);
Console.WriteLine(Environment.UserInteractive);
Console.WriteLine(Environment.WorkingSet);
Console.WriteLine(Environment.Is64BitOperatingSystem);
Console.WriteLine(Environment.Is64BitProcess);
Program Execution |150x150

7. Global namespace imports feature
Discussion and Demo
Implict Usings file
8. File-scoped namespaces feature
Discussion and Demo
9. SUMMARY / RECAP / Q&A
Discussion and Demo
10. What is next ?
Workspace
Notification Icon
Multiple Projects
Debugging
And more...
