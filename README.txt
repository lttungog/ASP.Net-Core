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

============================= RESEARCH =============================

F9: Toggles a breakpoint on the current line. 
Breakpoints allow you to pause the execution of your program during debugging

F5: Starts debugging your application (or continues if paused). 
If there are no breakpoints, it will run the application as usual.

Shift + F5: Stops the current debugging session.

F10: Steps over the next line of code during debugging, 
meaning it will execute the line but won't step into functions/methods.

Shift + F10: Opens the context (right-click) menu for the currently selected item, 
similar to pressing the right mouse button.

F11: Steps into the next function or method during debugging,
allowing you to move into the details of that code.

Shift + F11: Steps out of the current function/method, returning to the point where it was called

=====================================================================

3. Creating a new Controller

- right click on "Controllers" -> Add -> Controller -> Select "MVC Controller ..." -> select it again
- !!! when naming Controller, MUST include "Controller" in name

4. Creating a new View

- in the newly created Controller, right click on "Index" from "public IActionResult Index()"
- click "Add View" -> select "Razor View ...." -> select it again
- enter a name for the cshtml file -> click Add

5. Accessing newly created View (in current example "ProductController" -> View "Product")

- edit the newly created cshtml file in the new view folder
- run the main controller (in current example is "HomeController")
- in the link add "/product"