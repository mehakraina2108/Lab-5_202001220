# Lab-5_202001220

- Name : Mehak Raina
- Student Id- 202001220
**************************
# Static Analysis:
Static analysis is a method of examining the source code of a software program without
executing it. Static analysis can help detect errors, bugs, vulnerabilities, and other quality issues
in the code. Static analysis tools can perform various tasks such as checking syntax, style,
logic, data flow, control flow, and security. Static analysis can improve the reliability,
performance, and maintainability of software by identifying and correcting defects early in the
development process.

# Static Analysis Tools:
Static analysis tools are software tools that analyze the source code of a program without
executing it. They can help developers find and fix errors, bugs, vulnerabilities, code smells, and
other quality issues in their code. Static analysis tools can also measure various metrics of the
code, such as complexity, readability, maintainability, test coverage, and documentation. Static
analysis tools can be integrated into the development process as part of the code editor, the
version control system, or the continuous integration pipeline. Some examples of static analysis
tools are SonarQube, PMD, ESLint, and Pylint.
********************************
The list of tools to use for Python are:
- Mypy
- Pylint
- Pyflakes
- Pycodestyle (pep8)
- Flake8
- Prospector
- Bandit

# The tool that I used for Python for Static Analysis is Pylint

# Installation of Pylint in terminal

- To install pylint in the system, we have to use the command - pip install pylint

![image](https://user-images.githubusercontent.com/124191847/225564467-2e25f67d-61c9-4e80-ba38-83c051b4313c.png)

# Selected Github Repository
- After installing pylint, I selected a github repository.
- Next, I analyzed some of its files.
- The link of the github repository is : https://github.com/LeeRenJie/100-days-of-code-in-python

# Analyzing files from the repository

1. File : Day005-Random_Password_Generator

![image](https://user-images.githubusercontent.com/124191847/225566524-afc22bd4-04d3-4c3a-be11-54c5b89d407f.png)

- Error : The errors are Bad indentation, trailing newlines, missing modules, invalid name
- Rating : 3.21/10

2. File : Day012-Number_Guessing_Game

![image](https://user-images.githubusercontent.com/124191847/225568298-123e4aae-a686-4595-bdbd-6c6950f0a1d3.png)

- Error : Some of the errors are Bad indentation, Trailing whitespace, Trailing newlines, Missing module docstring, missing function and unecessary elif after return
- Rating : 0.00/10

3. Day015-Coffee_Machine

![image](https://user-images.githubusercontent.com/124191847/225569740-9c13e00f-3253-48fc-ba73-8618ebb43ced.png)

- Error : The errors are missing module docstring, constant name, unecessary else after return
- Rating : 6.59/10

4. Day009-Silent_Auction

![image](https://user-images.githubusercontent.com/124191847/225570411-f6b731e4-4728-4aad-9180-3eae7c371fc0.png)

- Error : The errors are Bad indentation, Trailing whitespace, Missing module docstring, unable to import some modules, missing functions
- Rating : 0.00/10

5. Day002-Tip_CalculatorInRM

![image](https://user-images.githubusercontent.com/124191847/225571177-38bda69b-01a3-4b34-8819-b7eaa9af424f.png)

- Error : The errors are missing module and invalid name
- Rating : 7.14/10

6. Day010-Basic-Calculator

![image](https://user-images.githubusercontent.com/124191847/225571757-e9f0f8d5-cfc6-4877-9639-366a56e3cbbb.png)

- Error : The errors are Bad indentation, Trailing whitespace, Missing module docstring, unable to import modules, Missing function or method docstring
- Rating : 0.00/10

7. Day007-Hangman_Game

![image](https://user-images.githubusercontent.com/124191847/225572892-bba06724-f013-44f7-9deb-8e1304b3fe3d.png)

- Error : The errors are Bad indentation, Trailing whitespace, Missing module docstring, unable to import module and invalid name
- Rating : 2.81/10
