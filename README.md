# Node.JS Telosys 3 Template

This is a Telosys Template for code generation.
It's purpose is to generate the required C# MVC files after having provided a DSL model.

## Installation

1. Download the template.  
2. Provide your DSL model.  
3. Set the following project variable(1) in your telosys-tools.cfg file :  
```
ProjectVariable.SOLUTION_NAMESPACE=YOUR_PROJECT_NAME
```
4. Generate the code with Telosys.  
5. Navigate to the generated code's root folder.  
6. Copy it's content over your MVC project.  
7. Run the application.  

(1) : Replace "YOUR_PROJECT_NAME" with your custom project's name.
## Requirements

- A MVC project.

## Credits

- Made by [Romuald Tuffreau](https://github.com/romwaldtff).

## Thanks

- [Laurent Guerin](https://github.com/l-gu), creator of [Telosys Tools](https://sites.google.com/site/telosystools/).

## License

This project uses the [LGPL v3 License](https://www.gnu.org/licenses/lgpl-3.0.en.html) (See the LICENSE file in this repository).