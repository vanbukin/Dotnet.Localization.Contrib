# AspNetCore.Localization
Home of localized resources for common NET Standard (and .NET Core) assemblies

# How to build
1. Navigate to .sln file location directory
2. `dotnet publish -c Release`

# How to build nuget package
1. Navigate to .sln file location directory
2. `dotnet publish -c Release`
3. `dotnet pack -c Release /p:NuspecFile=Dotnet.Localization.Contrib.System.ComponentModel.Annotations.ru-RU.nuspec`