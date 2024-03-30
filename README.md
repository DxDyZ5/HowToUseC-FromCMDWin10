# How To Use C# From CMD in Windows 10

## Instructions

1. Click the Windows key   ![Windows Key](https://github.com/DxDyZ5/HowToUseC-FromCMDWin10/assets/122232315/f17bc3b8-69fd-48f8-9d4c-71ae3aaf1084)  on your keyboard, type cmd and run it as administrator. It will prompt a window asking for permission, click yes.

2. Navigate out of system32 by typing `cd` and the desired path, e.g., `C:\Users\manue\OneDrive\Escritorio`.

3. Open a new C# file by typing `notepad C#FromCMD.cs` in the command prompt. Click yes if prompted.

4. Write the following C# code:

   ```csharp
   using System;

   namespace CMDWIN10
   {
       class Program
       {
           static void Main(string[] args)
           {
               Console.WriteLine("Hello from the CMD");
               Console.Read();
           }
       }
   }

Save the file (Ctrl + S) and close it (Alt + F4).

5. Compile the C# file by typing:

`C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc C#FromCMD.cs` (note that this 
path could vary depending on the .NET framework version installed)

This invokes the csc compiler with its full path and compiles the file.

6. To run the compiled executable, type C#FromCMD.exe.

![image](https://github.com/DxDyZ5/HowToUseC-FromCMDWin10/assets/122232315/b587e454-4487-426d-9b02-048bec016a98)


# if we don't want to use the full path everytime

## Instructions

1.  Click the Windows key   ![Windows Key](https://github.com/DxDyZ5/HowToUseC-FromCMDWin10/assets/122232315/f17bc3b8-69fd-48f8-9d4c-71ae3aaf1084) on your keyboard, find the `setting` icon and click on it.
2.  In settings go to `System`, search for `About` and click on `Advanced system settings`. A window will emerge, click on `Enviroment Variables...`.
3.  Another window will emerge, go to the section `System variables`, scroll down, click once on `Path` variable and click on `Edit...`.
4.  To conclude, type the path `C:\Windows\Microsoft.NET\Framework\v4.0.30319` (note that this 
path could vary depending on the .NET framework version installed). 
