# CohMetrixCore

CohMetrixCORE is a .NET 6 implementation of Coh-Metrix for modern operating systems, a program that leverages natural language processing to analyze discourse. It computes a wide range of linguistic indices to assess various aspects of language in written or spoken text, enabling you to determine text quality, readability, and other specific properties. This system conducts in-depth analyses across multiple text dimensions, including simple indices like word frequency and sentence length, as well as more complex indices such as cohesion and syntactic complexity. CohMetrixCore can be employed in educational tutoring systems, research, and a variety of applications where in-depth text analysis is necessary.

## Dependencies

### Windows (CLI)

- .NET 6 Runtime installed on your machine [link](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.16-windows-x64-installer)
- ASP.NET Core 6 Runtime installed on yor machine [link](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-aspnetcore-6.0.16-windows-x64-installer)

### WIndows (Desktop)

- Mono for Windows (required for CohMetrixCoreGTK) [Download Mono](https://www.mono-project.com/download/stable/#download-win)

### Linux (CLI)

- .NET 6 Runtime

`sudo apt install dotnet`

- ASP .NET Runtime

`sudo apt install aspnet`

### Ubuntu (GTK)

- .NET 6 Runtime
-  GTK3

## Download

- Windows GTK: Use installer in repository
- Ubuntu GTK: Use the debian package in repository

### Windows (CLI)

`CohMetrixCoreCLI.exe <input file or directory> <output CSV>`

### Linux (CLI)

`CohMetrixCoreCLI <input file or directory> <output CSV>`

### Windows (GTK)

Installed in the Start Menu

### Linux (GTK)

`/user/bin/cohmetrixcoregtk/bin/CohMetrixCoreGTK`

## Licensing

New versions of CohMetrixCore will have a licensing schema. CohMetrixCore is provided free of charge, but to control it's integrity, we will ask all researchers to register. Please make an issue with the secret key that the app generates.
