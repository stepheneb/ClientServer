Two-way C# client/server implementation using async-based sockets.

Open repo in Visual Studio right-click on **ClientServer** solution and select **Set Startup Projects...** and configure to run both  **Server** and **Client** projects.

Implementation based on examples in the Microsoft .NET documentation:

- [Asynchronous Server Socket Example](https://docs.microsoft.com/en-us/dotnet/framework/network-programming/asynchronous-server-socket-example)
- [Asynchronous Client Socket Example](https://docs.microsoft.com/en-us/dotnet/framework/network-programming/asynchronous-client-socket-example)
- [Using an Asynchronous Server Socket](https://docs.microsoft.com/en-us/dotnet/framework/network-programming/using-an-asynchronous-server-socket)

NOTE:

Installing extension [SwitchStartupProject](https://bitbucket.org/thirteen/switchstartupproject/src) on Windows Visual Studio  will display pulldown menu on toolbar to left of **Start** button with named option **Server and Client**.