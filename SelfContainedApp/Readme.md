# Console app
Simple C# console app targeting .NET 5
## Build & publish
### Normal
dotnet publish -c Release -r win-x64
### SelfContained
dotnet publish -c Release -r win-x64 --self-contained true 
### SelfContainedTrimmed
dotnet publish -c Release -r win-x64 --self-contained true -p:PublishTrimmed=true