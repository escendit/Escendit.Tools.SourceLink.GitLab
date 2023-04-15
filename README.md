# NuGet Package: Escendit.Tools.SourceLink.GitLab
.NET NuGet package
that simplifies the process of integrating [SourceLink](https://github.com/dotnet/sourcelink) into your project.
SourceLink provides a mechanism for debugging optimized code
without sacrificing security by allowing you to use the actual source code for debugging,
rather than decompiled code.

## Installation
To install `Escendit.Tools.SourceLink.GitLab`,
you can use the NuGet Package Manager or run the following command in the Package Manager Console:

```shell
PM> Install-Package Escendit.Tools.SourceLink.GitLab
```
Or you can search for "Escendit.Tools.SourceLink.GitLab"
in the NuGet Package Manager UI and install it from there.

## Usage
`Escendit.Tools.SourceLink.GitLab` provides properties for SourceLink
that you can use in your .NET projects.
These default values are intended to simplify the process of integrating SourceLink into your project,
by source-linking files from GitLab repository to your NuGet package and can be overridden as needed.

## Limitations
Using the current git technology stack, there are limitations in being able
to access source files of private repositories due to the security mechanisms in place.

## Contributing
If you find a bug or have a feature request, please create an issue in the GitHub repository.

To contribute code, fork the repository and submit a pull request.
Please ensure that your code follows the project's coding standards and is thoroughly tested.

## License
This package is released under the MIT License. See the LICENSE.txt file for details.
