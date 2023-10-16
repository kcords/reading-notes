### Classes and Objects

1. What are the key differences between classes and objects in Python, and how are they used to create and manage instances of a class?

    - A *class* defines the structure of an object and and acts as a template for how objects created from the class will behave by creating a container for the variables and functions to exist within a single entity
      ```
      class NewClass:
          def __init__(name):
              self.name = name
      ```
    - An *object* is a data entity that is its own individual copy or instance of a class, containing its own attribute values and methods following the template of the class it was created from
      ```
      object = NewClass('New Object')
      ```

### Recursion

2. Explain the concept of recursion and provide an example of how it can be used to solve a problem in Python. What are some best practices to follow when implementing a recursive function?

    - A recursive function divides the problem to be solved into smaller portions, then calls itself repeatedly until reaching a "base case" where the problem cannot or should not be divided any further, at which point it returns the results
    - State should be maintained either globally or by passing it to each subsequent call
    - Caching can reduce inefficiency caused by recalculating  or recomputing the same solutions repeatedly
    - Keep in mind the number of times the function will need to be called to avoid a stack overflow

### pytest

3. What is the purpose of pytest fixtures and code coverage in testing Python code? Explain how they can be used together to improve the quality and maintainability of a project.

    - `Fixtures` provide a way to set up and tear down common test data for each test ensuring consistency and reusability
    - `Code coverage` refers to the measure of percentage of your code that is ran during testing. 100% coverage would mean every line of code has been run during testing
    - They can be used together to ensure that you have consistent and robust testing that will thoroughly and reliably test your code the same way each time tests are ran


### References

- [Classes and Objects](https://www.learnpython.org/en/Classes_and_Objects)
- [Thinking recursively](https://realpython.com/python-thinking-recursively/#maintaining-state)
- [Testing with pytest](https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage)