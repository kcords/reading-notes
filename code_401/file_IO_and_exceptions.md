### Reading and Writing Files

1. What is the purpose of the `with` statement when opening a file in Python, and how does it help manage resources while reading and writing files?
    - The `with` keyword utilizes a context manager (built in by default, or a custom one can be utilized) that will automatically close the file once the end of context block is reached.

2. Explain the difference between the `read()` and `readline()` methods for file objects in Python. Provide examples of when to use each method.
     - `read` - Reads the entire content of the file and returns it as a string
       - Can be useful for smaller files where the full text is needed
     - `readline` - Will read one individual line from the file at a time until it reaches a `'\n'` or the end of the file.
       - Best when you want to examine the file contents line by line, or for large files to control how much is stored in memory at a time.

### Exception Handling

1. Briefly describe the concept of exception handling in Python. How can the `try`, `except`, and `finally` blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.
    - `try` - This will be the code that is ran
    - `except` - Will run if there is an exception in the `try` block
      - Error can also be captured using `except Exception as error`
    - `finally` - Will be run after the `try`/`except` code has completed
    - _Example:_
      ```
      try:
        function_to_call(arg)
      except:
        print('Oops, that function call didn't work :'(')
      finally:
        print('Yay, it's over!')
      ```