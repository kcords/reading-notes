### Testing and Recursion

1. What are the key principles of Test-Driven Development (TDD) in Python, and how do they contribute to the overall quality of code?
      - Write descriptive test names that say what we are testing and what is expected
      - Tests should be written before any code, making clear what the expected output will be with a given input
      - The test filename should match the convention of the module file to be tested
      - AAA: Arrange, Act and Assert
        - *Arrange* input data
        - *Act* - execution of code
        - *Assert* that the actual output matches what is expected
      - Process:
        - Write the currently failing test
        - Write the feature and ensure a passing test
        - Refactor code as needed

2. Explain the purpose of the `if __name__ == '__main__':` statement in Python scripts. What are some use cases for including this conditional in your code?
     - It enables testing of the code within a file when it is ran directly, but ignores the function invocation when it is imported as a module

3. Describe the concept of recursion in Python.
    - Creating a block of code that can be repeatedly called, breaking down the dataset into smaller portions until reaching the base case condition, allowing for simpler, concise code
4. What is the difference between Python modules and packages? Explain how to create, import, and use them in your Python programs.
    - A module is a single Python file containing related code that can be imported into another file.
      - *Import*: `import module_name`
      - *Use*: `module_name.variable`
    - A package is a collection of Python modules
      - *Create*: Within a directory, create a `__init__.py` file and add other modules to the same folder
      - *Import*: `import package_name` (based off package directory name)
      - *Use*: `package_name.module`

### References
- [TDD with Python](https://code.likeagirl.io/in-tests-we-trust-tdd-with-python-af69f47e6932)