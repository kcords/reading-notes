### List Comprehensions
1. What is the basic syntax of Python list comprehension, and how does it differ from using a for loop to create a list? Provide an example of a list comprehension that squares the elements in a given list of integers.
   - Syntax: `[expression for item in iterable if optional_condition]`
   - Differences include concise, single line code as well as an automatically returned list
   - Example: `[x ** 2 for x in my_list]`


### Decorators
2. What is a decorator in Python?
   - A simplified syntax for calling higher order functions
   - It extends a function without directly modifying it

3. Explain the concept of decorators in Python. How do they work, and what are some common use cases for them? Provide an example of a simple decorator function from the reading.
   - They work by wrapping a function with another function to add functionality before or after the original function. They can simplify code reuse, provide separation of concerns, or extend the functionality of functions/methods.
   - Some common uses are timing, debugging, caching, and delay functions
   - Caching example [from text](https://realpython.com/primer-on-python-decorators/#caching-return-values):
      ```
      import functools
      from decorators import count_calls

      def cache(func):
          """Keep a cache of previous function calls"""
          @functools.wraps(func)
          def wrapper_cache(*args, **kwargs):
              cache_key = args + tuple(kwargs.items())
              if cache_key not in wrapper_cache.cache:
                  wrapper_cache.cache[cache_key] = func(*args, **kwargs)
              return wrapper_cache.cache[cache_key]
          wrapper_cache.cache = dict()
          return wrapper_cache

      @cache
      @count_calls
      def fibonacci(num):
          if num < 2:
              return num
          return fibonacci(num - 1) + fibonacci(num - 2)
      ```

