
# CohMetrixCore

[link](http://cohmetrix-new.memphis.edu/home)

CohMetrixCORE is a .NET 6 implementation of Coh-Metrix for modern operating systems, a program that leverages natural language processing to analyze discourse. It computes a wide range of linguistic indices to assess various aspects of language in written or spoken text, enabling you to determine text quality, readability, and other specific properties. This system conducts in-depth analyses across multiple text dimensions, including simple indices like word frequency and sentence length, as well as more complex indices such as cohesion and syntactic complexity. CohMetrixCore can be employed in educational tutoring systems, research, and a variety of applications where in-depth text analysis is necessary.


# Announcment (Licensing)

A Linux and MacOS version is now available for testing. We are also changing our registration process soon to correspond with a new web tool release.  

We will no longer be generating licenses for the MacOs and Linux Versions. You may use the self service portal at [link](http://cohmetrix-new.memphis.edu/home) Windows users will be migrated over soon.

## Upgrading

Upgrades to the newest build may require redownloading the data. Please delete these folders if you have them:

``C:\Program Files (x86)\CohMetrixCore\data (Windows)``
``~/.local/share/CohMetrixCore (Linux and MacOS)``

Cohmetrix will automatically redownload the files.


## Licensing

We are testing a new licensing scheme that will generate licenses automatically with a web portal registration. For now, when the software asks for a email or API key, just enter anything. Since that will return an error, it will ask you for your registration key as described below:

New versions of CohMetrixCore will have a licensing schema. CohMetrixCore is provided free of charge, but to control it's integrity, we will ask all researchers to register. Please use this form [link](https://github.com/memphis-iis/cohmetrix-issues/issues/new) to make an issue with the secret key that the app generates.

### Example Prompt:
![image](https://github.com/memphis-iis/cohmetrix-issues/assets/46696077/04e47f73-d30c-4784-8b9f-384cc325c923)


### Example Issue:

Name:

Email:

Insitution:

Secret key:

Description of your research:

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

## Download

- Windows: Use installer in repository - dont use the GTK version, it's experimental.
- Ubuntu GTK: Use the debian package in repository

### Windows (CLI)

`CohMetrixCoreCLI.exe <input file or directory> <output directory>`

### Linux / MacOS (CLI)

`CohMetrixCoreCLI <input file or directory> <output directory>`









