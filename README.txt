1. Installation of Nuget (for project organization)

- open Visual Studio
- go to Tools -> NuGet Package Manager -> Package Manager Console (open it)
- go to "nuget.org" -> go to Packages -> select package and copy
- !!! go back to terminal opened in Visual Studio -> "cd .\"project_name" (without this, it will not install)
- paste in the code copied from "nuget.org" -> example: dotnet add package Newtonsoft.Json --version 13.0.3
- Install

2. Managing NuGet Packages

- open Visual Studio
- go to Tools -> NuGet Package Manager -> Manage NuGet Packages for Solution.. (open it)
- multiple tabs on top -> go to browse to install/uninstall/update/etc..