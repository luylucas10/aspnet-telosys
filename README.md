# Telosys 3 MVC C# Template

This is a C# MVC application Telosys Template.  
Template purpose : generate the MVC C# files based on your database/dsl model.

The generated files provide the Controllers, Models and Views. You can use them easily with your Visual Studio project.

## Requirements

- Microsoft SQL Server.
- A Web Application MVC Visual Studio project with EntityFramework installed (via nuget).

## Installation

1. Download the template.
2. Provide your DSL/Database model.
3. Configure the `ProjectVariable.SOLUTION_NAMESPACE` variable in the `telosys-tools.cfg` file of your Telosys project.  
Example :`ProjectVariable.SOLUTION_NAMESPACE=project`
4. Generate the code with Telosys.  

## Getting started

- Import the generated files in your project and run it.

## Credits

- Made by [Romuald Tuffreau](https://github.com/romwaldtff).

## Thanks

- [Laurent Guerin](https://github.com/l-gu), creator of [Telosys Tools](http://www.telosys.org/).

## License

This project uses the [LGPL v3 License](https://www.gnu.org/licenses/lgpl-3.0.en.html) (See the LICENSE file in this repository).