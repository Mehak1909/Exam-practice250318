The WMI command-line (WMIC) utility provides a command-line interface for Windows Management Instrumentation (WMI). WMIC is compatible with existing shells and utility commands. 

An alias is a friendly renaming of a class, property, or method that makes WMI easier to use and read. 

A switch is a WMIC option that you can set globally or optionally

Returns the result of the Associators of (<wmi_object>) query where <wmi_object> is the path of objects returned by the PATH or CLASS commands. 

Creates a new instance, and sets the property values.

Here is somelinks which i will give below the line
[1st Link](https://learn.microsoft.com/en-us/windows/win32/wmisdk/wmic)
Example:Disk Drive Information: To list all disk drives and their details:
cmd

wmic diskdrive get caption, size, model
[2nd Link](https://www.techtarget.com/searchenterprisedesktop/definition/Windows-Management-Instrumentation-Command-line-WMIC)
Example: Memory Information: To retrieve information about the physical memory:
cmd

wmic memorychip get capacity, speed, manufacturer
[3rd Link](https://en.wikipedia.org/wiki/Windows_Management_Instrumentation)
Example: Video Controller (Graphics Card) Information: To obtain details about the video controller:
cmd

wmic path win32_videocontroller get caption, adapterram, driverversion
