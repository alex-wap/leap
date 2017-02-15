# C# Notes 

## Resources

[Tutorial - Getting Started](https://www.microsoft.com/net/tutorials/csharp/getting-started)


[Troubleshooting](https://www.microsoft.com/net/tutorials/csharp/getting-started/troubleshooting)


[Learn C# in Y Minutes](https://learnxinyminutes.com/docs/csharp/)


[Compile C# Online](http://rextester.com/)


## Notes

* one namespace for standard .NET Framework Class Library
```using System;```
* Namespaces define scope to organize code into modules
* Each .cs file should at least contain a class with the same name as the file.
* `Console.WriteLine("Hello World");`
* `Console.Write("Hello ");Console.Write("World");` write to the same line
* Types: 
  * sbyte
  * byte
  * short
  * ushort
  * int
  * uint
  * long
  * ulong
  * double
  * float
  * decimal
  * bool
  * char
  * string
* Strings:
  * `string.Compare(fooString, "x", StringComparison.CurrentCultureIgnoreCase);`
  * `string fooFs = string.Format("Check Check, {0} {1}, {0} {1:0.0}", 1, 2);`
  * newlines:
  ```csharp
  string bazString = @"line 1
  line2
  line3";
  ```
* DateTime:
```csharp
  DateTime fooDate = DateTime.Now;
  Console.WriteLine(fooDate.ToString("hh:mm, dd MMM yyyy"));
```


