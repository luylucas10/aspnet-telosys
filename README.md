# Telosys templates for C# web MVC application

This bundle of templates is designed to generate a C# web MVC application with Telosys.

This bundle provides a set of templates to generate Controllers, Models and Views.

## Requirements

- Microsoft SQL Server.
- A Web Application MVC Visual Studio project with EntityFramework installed (via nuget).

## Installation

1. Define all your domain entities in a model

2. Use Telosys to download and install this bundle of templates

3. Define the `SOLUTION_NAMESPACE` project variable 
In `telosys-tools.cfg` file : set `ProjectVariable.SOLUTION_NAMESPACE` 
Example :`ProjectVariable.SOLUTION_NAMESPACE=project`

4. Generate the code with Telosys.  


## Credits

- Bundle initially created by [Romuald Tuffreau] (https://github.com/romwaldtff).

## Thanks

- [Laurent Guerin](https://github.com/l-gu), creator of [Telosys Tools](http://www.telosys.org/).

## License

This bundle is free and Open Source
[LGPL v3 License](https://www.gnu.org/licenses/lgpl-3.0.en.html) (See the LICENSE file in this repository).

