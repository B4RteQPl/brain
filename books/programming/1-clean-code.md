[Order Clean Code: A Handbook of Agile Software Craftsmanship on Amazon](https://www.amazon.com/dp/0132350882?&_encoding=UTF8&tag=architect011b-20&linkCode=ur2&linkId=9c101d8b9ded0b65d001bac670298715&camp=1789&creative=9325)

This list of concepts from *Clean Code* by Robert C. Martin is highly useful for programmers as it covers essential techniques and principles for writing clean, maintainable, and reliable code.

Here is a list of essential coding concepts from book:

* Naming conventions:
	* Importance:
		- Meaningful and consistent names are essential for code clarity and readability. 
		- Names should reflect the purpose and behavior of the variable, function, or class. 
	* Consistent usage:
		- Variables, functions, and classes should have consistent naming conventions across the codebase. 
		- Avoid using abbreviations, acronyms, or numbers in names, except where necessary and well-known.

* Functions:
	* Small and focused:
		- Functions should have a clear purpose and responsibility. 
		- Functions should be short enough to fit on one screen, and not exceed 20 lines of code.
	* Limited parameters:
		- Functions should have a limited number of input parameters to reduce complexity and improve readability. 
		- Prefer passing objects or structs instead of multiple individual variables.
	
* Comments:
	* Proper usage:
		- Comments should explain the intention behind the code, not the code itself. 
		- Avoid redundant or misleading comments, as they can become outdated and confuse readers.
	* When to use:
		- Use comments to explain complex or obscure code, or to provide context for future maintainers. 
		- Use comments to document APIs or public interfaces for users.

* Formatting:
	* Effective organization:
		- Code should be organized in a logical and consistent manner, with a clear separation of concerns. 
		- Use whitespace and indentation to improve code readability and structure.
	* Naming and casing:
		- Use consistent naming conventions for files, directories, and other components of the codebase. 
		- Use camelCase for variables and functions, and PascalCase for classes and interfaces.

* Error handling:
	* Techniques:
		- Use try-catch blocks to handle exceptions and recover from errors gracefully. 
		- Prefer using specific exception types over generic catch-all exceptions. 
	* Minimization:
		- Avoid using try-catch blocks for control flow, as they can make code difficult to follow. 
		- Handle errors at the appropriate level of abstraction, and don't catch exceptions you can't handle.

* Objects and data structures:
	* Encapsulation and abstraction:
		- Use encapsulation and abstraction to limit access to data and behavior. 
		- Avoid exposing implementation details to the outside world.
	* Data hiding:
		- Hide implementation details of an object or data structure from other parts of the system.
		- Provide well-defined interfaces for accessing and modifying data.

* Code smells:
	* Recognition:
		- Learn to recognize common bad code patterns, such as duplication, long methods, and excessive coupling. 
		- Use code analysis tools to help identify and refactor code smells. 
	* Refactoring:
		- Refactor code to eliminate code smells and improve code quality. 
		- Refactoring should be done continuously and in small steps to minimize risks.

* Test-driven development:
	* Importance:
		- Writing tests is crucial for ensuring code reliability and maintainability. 
		- Tests provide a safety net for refactoring and prevent regressions. 
	* Writing tests:
		- Write tests first, before writing production code. 
		- Write tests that cover all possible scenarios and edge cases.

* Refactoring:
	* Purpose:
		- Refactoring is the process of improving code quality and structure without changing its behavior.
		- Refactoring should be done continuously to keep code clean and maintainable. 
		- Refactoring should be done in small, focused steps to minimize risks and make changes more manageable. 
* Techniques:
	- Use code smells and automated tools to identify areas of code that need refactoring. 
	- Refactor code using proven techniques such as extracting methods, consolidating duplicate code, and eliminating dead code.
	