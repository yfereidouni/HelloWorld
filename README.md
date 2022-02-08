# HelloWorld using for Azure DevOps Pipelines using Docker and Kubernetes

Hosting .NET Core console-app as Windows service :

To run as a console-app:

dotnet run

To install as a Windows service, first publish targetting Windows:

dotnet publish HelloWorld.csproj -r win10-x64

and then use the HelloWorld install command on the .exe file:

cd HelloWorld\bin\Debug\net6.0\HelloWorld.exe install
