## Coding Guidelines

### 1. Naming Conventions:
* Always use meaningful, self-explanatory names for variables, functions, and classes
* For functions, variables, and attributes, use lowercase_with_underscores
* PascalCase for classes
* Constants and env variables: ALL_CAPS_WITH_UNDERSCORES

### 2. Code Structure:
* Always use consistent indentation (4 spaces). Don't mix spaces and tabs
* Use absolute imports when possible. Avoid wildcard imports (from module import *)
* Use type hints for all function arguments
* Functions should be modular, short, and should focus on a single task
* Group similar classes or modules into their own files where possible
* Prefer f-strings for string formatting when possible
* Don't hardcode configuration values in the source code, use env variables instead

### 3. Comments
* Write clear comments for each block of code, function, class, module
* Try to explain "why" and "how" instead of "what"
* For each file, include instructions on how it should be used, why it's required, and what it does in the beginning

### 4. Error Handling:
* Always wrap any potentially unstable code in try/except blocks
* Return meaningful error logs for all scenarios with sufficient info for easy debugging

### 5. Version Control:
* Use meaningful commit messages
* Exclude unnecessary files with .gitignore
* Never include API keys and hardcoded credentials in commits. Use Github secrets
* Prepare a requirements.txt with exact version for all packages for easy replication on other machines

### 6. Others:
* ALWAYS double verify all AI generated code line by line
* Use virtual environments to avoid mixing project dependencies
