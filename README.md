<h2 align="center">
    EF Core Tool
</h2>
<h3 align="center">
    <img src="https://github.com/khanhtungmtp/ef-core-tools/blob/images/vietnam.gif?raw=true" align="center">
</h3>

## Goal

> - C# Snippet MTP aims to increase the use of vscode editor as the master tool for console, web and game development in C# Programming Language providing the same shortcuts, efficiency, intellisense that is offered by Visual Studio Community.
> - One of the first objectives is to reduce the amount of extensions downloaded for C# reducing the time and effort on configuration that has to be done by the user as well as to avoid extensions conflicts. Also great features to speed up your development workflow.

## Current features

> - **_Fix_**: Classes, Interfaces, and other types created correctly even when the user type incorrect names.
> - **_New Features added_**: Added a default folder for project creation. Add this configuration to your settings with your path: `"ef-core-tool.defaultFolderForProjectCreation": "D:\\"` **{Your path}**
> - **_New Features added_**:
> - **_Add Project to a Solution_** : Capability to add projects to the same solution with a click of a button. You can select a different project framework as well as the template.
>
> ![Add Project](https://github.com/khanhtungmtp/ef-core-tools/blob/master/images/addProject.png?raw=true)
> ![Menu](https://github.com/khanhtungmtp/ef-core-tools/blob/master/images/menu.png?raw=true)
> - **_Submenu With Options_** :
>   - Create Class
>   - Create Interface
>   - Create Record
>   - Create Struct
> - **_Fix_**: .NET target frameworks list on project creation are based on OS and SDKs installed.
> - **_Enhancement_**: Design patterns snippets added. It will create a commented pattern code to be used as reference
> - **_singleton_** : Creational singleton pattern
> - **_factoryMethod_** : Creational factory method pattern
> - **_adapter_** : Structural adapter pattern
> - **_observer_**: Structural observer pattern
> - **_Enhancement_**: Regex snippet cheat sheet added.
> - **_regex_** : Regex cheat sheet
> - When creating classes or interfaces system will consider if you have a `<RootNamespace>`YourUniqueNamespace`</RootNamespace>` tag on your **_.csproj_**. If the tag is not found system will use your project name as your root namespace
> - Added command to create Class from the context/menu
> - Added command to create Interface from the context/menu
> - How to use:
>   - Right click in the project folder or any folder inside of your project folder and select either Create Class or Create Interface
>   - Give it a name of your file and class or interface will be created automatically in the selected folder
>
### Command to Create Solution or Project

> Command to create projects
>
> Press CTRL + SHIFT + P: Then type: Create Project
> [ C# Toolbox: Create Project ]
>
> > ![Create Project](https://github.com/khanhtungmtp/ef-core-tools/blob/master/images/createproject.PNG?raw=true)
>
> - Projects templates supported:
> - Blazor Server App
> - Blazor WebAssembly App
> - Console Application
> - Class Library
> - .NET Core: Empty, MVC, Razor Page, Angular SPA, React SPA, React/Redux SPA, Web Api, GRPC Services, Razor Class Library
>
> - Added snippets for creating arrays, lists and dictionaries using var
>   - var myArray = new type[size];
>   - var myList = new List\<type>();
>   - var myDictionary = new Dictionary\<type,type>();

## How to use

> - All the snippets comments are shown as -> snippet name
> - Snippets were created thinking on MTP and the extensive use of tab key
>
> ![Add var, class, function](https://github.com/khanhtungmtp/ef-core-tools/blob/master/images/clipvarclassfunc.gif?raw=true)
>
> ![Add property, dictionary](https://github.com/khanhtungmtp/ef-core-tools/blob/master/images/clippropdic.gif?raw=true)
>
> - Colored comments were created to increase visibility of todo's, reviews, bugs and research
>
> ![Add list, comments](https://github.com/khanhtungmtp/ef-core-tools/blob/master/images/cliplistcom.gif?raw=true)

## Do you want to contribute?

### Guidelines

> 1. **Fork** the original repository to your own repository
> 2. **Clone** it to your local
> 3. **Contribute to it**
> 4. **Push** it to your remote repo
> 5. Send a **PR** `[Pull Request]` to the master repo
> 6. Your contribution will be evaluated then we will merge your changes with the original repository. ❤

**Enjoy!**
