# Root Directory and Root Path in .NET
+ .NET Core
+ .NET Core 8.0
+ .NET 8.0

```
IWebHostEnvironment, ContentRootPath  	  // D:\Dev\WebApp\

Path.GetFullPath("temp")                        // D:\Dev\WebApp\temp

Directory.GetCurrentDirectory()                 // D:\Dev\WebApp\temp

Environment.CurrentDirectory                    // D:\Dev\WebApp\temp

AppContext.BaseDirectory                        // D:\Dev\WebApp\bin\Debug\net8.0\

AppDomain.CurrentDomain.BaseDirectory           // D:\Dev\WebApp\bin\Debug\net8.0\

Assembly.GetExecutingAssembly().Location        // D:\Dev\WebApp\bin\Debug\net8.0\Test.exe
```
