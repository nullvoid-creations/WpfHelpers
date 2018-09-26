# WPF Helpers

WPF helpers is set of classes and resources wrapped up in an assembly to get up to speed with a new WPF MVVM based project targeting .NET Framework 4.0. As this targets framework 4.0, should work with .NET 4+ as well (haven't tested it though). As of now this assembly provides below mentioned features.

* **CommandBase** is an abstract class which provides boilerplate implemention for commanding.
* **NotificationBase** is an abstract class which provides boilderplate implementation for raising notifications.
* **ViewModelBase** is an abstract class which provides boilerplate implementation for making view models. It has additional methods like GetView which searches and creates an instance of View and injects view model as DataContext, ShowDialog and HideDialog to show and hide a view as modal dialog respectively, IsInDesignMode property tells if a view is open in designer, etc.
* **RelayCommand** allows you to execute methods as commands. It allows callbacks and async execution.
* **AssemblyInformation** gives you metadata of passed in assembly's instance.
* **DirectoryWalker** lets you recursively traverse directories without running into stack overflows as its implementation relies on heap and not recursion.
* **PlatformInvoke** encapsulates certain methods which are not directly supported by .NET framework like run a program with user name and password, activate another window, get a window's handle, toggle a caret on textbox, hide a window, minimize a window, show a window, get public desktop directory, get start menu directory, select a folder, create a shortcut, etc.
* **SettingsManager** allows saving of settings in an encrypted file.
* **ZipStorer** allows compression and decompression of ZIP archives.
* **ColumnHeaderBehaivor** is a custom behavior to auto generate column headers of DataGrid based on annotation. It allows hiding of columns too.
* **PasswordBoxBindingBehavior** allows binding password of a password box to a string property.

This package is available via nuget [here](https://www.nuget.org/packages/NullVoidCreations.WpfHelpers/), execute below mentioned command in nuget console.
```
Install-Package NullVoidCreations.WpfHelpers
```
# Licensing

Licensing is a component which developers can use in thier projects to incorporate machine bound licenses for their softwares. This package is available via nuget [here](https://www.nuget.org/packages/NullVoidCreations.Licensing/), execute below mentioned command in nuget console to include it.
```
Install-Package NullVoidCreations.Licensing
```
# Acknowledgements

Many thanks to [JetBrains](https://www.jetbrains.com/) for providing free license of their .NET toolbelt. If you come across any issues or want new features added, kindly report/request them [here](https://github.com/waliarubal/WpfHelpers/issues).

![JetBrains](https://upload.wikimedia.org/wikipedia/commons/thumb/1/1a/JetBrains_Logo_2016.svg/220px-JetBrains_Logo_2016.svg.png "JetBrains Logo")

Following projects rely on WPF Helpers and/or the Licensing component.
* [eBay Smart Buy - Books](https://github.com/waliarubal/EbayWorker) which is a smart wat to get competitive prices for books from eBay.
* [SMS Buddy](https://github.com/waliarubal/SmsBuddy) which is an innovative smart way to send SMS in bulk using templates.
* [JustDial Scraper](https://github.com/waliarubal/JustDialScrapper) which is an innovation to bulk download contact information from JustDial. 
* [Chaturbate Player](https://github.com/waliarubal/ChaturbatePlayer) which is a redefined way to view live cam feeds from chaturbate.com without opening it in web browser. 
* [Billiards Club Manager](https://github.com/waliarubal/BilliardsClubManager) which is a billiards club management software,
