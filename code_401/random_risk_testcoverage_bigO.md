
1. How can the random module be utilized in Python to generate random numbers or make selections from a list, and what are some common functions available within the module?
    **Common functions:**
     - `randint(x, y)` generates a random *int* within a provided range, with `x` being a lesser value than `y`
     - `random()` generates a *float* between 0 and 1
     - `choice(coll)` returns a random element from a provided collection
     - `choices(coll, k=x)` generates and returns a list of `x` elements from a provided `coll`
     - `shuffle()` takes elements in a collection and shuffles them in place
     - `randrange(start, stop, step)` returns an *int* between the `start` and `stop` values at the provided `step` interval

2. In the context of software development, what is risk analysis, and what are the key steps involved in conducting a risk analysis for a software project?
   - Identifying and subsequently testing areas with the potential to cause problematic or unwanted behavior
   **Steps:**
      1. Searching the risk
      2. Analyzing the impact of each individual risk
      3. Measures for the risk identified

3. What is test coverage and why is it an important (or potentially misleading) metric in software testing?
   - Test coverage refers to a metric measuring the amount of code that is tested vs untested
   - It can help give insight into what code is being tested, but can be deceptive in the quality of those tests. Lots of tests != quality tests.

4. What is Big O notation, and how is it used to describe the performance of an algorithm? Give an example of an everyday task (not software related) that demonstrates O(n) time complexity.
   - Big O is a representation of the worst-case time or space complexity of an algorithm and can be used to determine the algorithms efficiency
   - Waiting in line to order a drink at a coffee shop would be an example of O(n) time complexity. It will take the completion of `n` orders ahead of you before you can place an order (as I would have to assume you are at the end of the line).

### References
- [Random module in Python](https://www.pythonforbeginners.com/random/how-to-use-the-random-module-in-python)
- [Risk Analysis in Software Testing](https://www.edureka.co/blog/risk-analysis-in-software-testing/)
- [Test Coverage](https://martinfowler.com/bliki/TestCoverage.html)