
# CohMetrixCore

[link](http://cohmetrix-new.memphis.edu/home)

CohMetrixCORE is a .NET 7 implementation of Coh-Metrix for modern operating systems, a program that leverages natural language processing to analyze discourse. It computes a wide range of linguistic indices to assess various aspects of language in written or spoken text, enabling you to determine text quality, readability, and other specific properties. This system conducts in-depth analyses across multiple text dimensions, including simple indices like word frequency and sentence length, as well as more complex indices such as cohesion and syntactic complexity. CohMetrixCore can be employed in educational tutoring systems, research, and a variety of applications where in-depth text analysis is necessary.


# Announcment (Licensing)


We will no longer be generating licenses for all versions unless there is an issue with the self service portal.. You may use the self service portal at [link](http://cohmetrix-new.memphis.edu/home) 

## Upgrading

Upgrades to the newest build may require redownloading the data. Please delete these folders if you have them:

``C:\Program Files (x86)\CohMetrixCore\data (Windows)``
``~/.local/share/CohMetrixCore (Linux and MacOS)``

Cohmetrix will automatically redownload the files.

## Dependencies

### Windows (CLI)

- .NET 6 Runtime installed on your machine [link](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.16-windows-x64-installer)
- ASP.NET Core 6 Runtime installed on your machine [link](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-aspnetcore-6.0.16-windows-x64-installer)

### Windows (Desktop Non GTK)

- .NET 6 Runtime installed on your machine [link](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.16-windows-x64-installer)
- ASP.NET Core 6 Runtime installed on yor machine [link](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-aspnetcore-6.0.16-windows-x64-installer)

### MacOS Silicon

- .NET 6 Runtime installed on your machine [link](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-6.0.26-macos-arm64-installer)
- ASP.NET Core 6 Runtime installed on yor machine [link](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-aspnetcore-8.0.1-macos-arm64-binaries)


### MacOS Classic
- .NET 6 Runtime installed on your machine [link](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-6.0.26-macos-x64-installer)
- ASP.NET Core 6 Runtime installed on yor machine [link](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-aspnetcore-6.0.26-macos-x64-binaries)



### Linux (CLI)

- .NET 6 Runtime

`sudo apt install dotnet`

- ASP .NET Runtime

`sudo apt install aspnet`

### Windows (CLI)

`CohMetrixCoreCLI.exe <input file or directory> <output directory>`

### Linux / MacOS (CLI)

`CohMetrixCoreCLI <input file or directory> <output directory>`









