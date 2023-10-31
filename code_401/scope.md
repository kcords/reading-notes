1. Explain the concept of variable scope in Python and describe the difference between local and global scope. Provide an example illustrating the usage of both.
   - `local` scope is created any time a function is called. The code contained within that function is the local scope, and references to declared values outside of that scope will not be recognized.
   - `global` scope is accessed at the top application or module level. It can be accessed anywhere within the application or containing module.
   - Global scope would ideally contain values that are not going to be changed, whereas local scope can contain values that can be assigned temporarily, modified, then discarded when no longer needed, such as once the function has returned its desired value.

2. How do the global and nonlocal keywords work in Python, and in what situations might you use them?
   - `global` and `nonlocal` both allow local access to globally defined variables
   - `global` allows modifying of a variable that exists in the global scope
   - `nonlocal` allows modifying of a variable that exists in an enclosing scope

3. In your own words, describe the purpose and importance of Big O notation in the context of algorithm analysis.
   - Big O is a universal way to describe how the efficiency of an algorithm will scale with the input size. It is a way to help us make sure we're choosing the right algorithms for optimized performance, especially when working with large datasets.

4. Based on the Rolling Dice Example, explain how you would simulate a dice roll using Python. Describe how you would use code to calculate the probability of rolling a specific number (e.g., the probability of rolling a 6) over a large number of trials.
   - I'd start by either creating a variable to track the rolls of a single number, or a dict to count all roll possibilities.
   - Then I'd create a loop and use the imported random module to get a number between 1 and 6 corresponding to the counts on real dice, tracking the count in the variable.
   - Once the loop exits, I would divide the count an individual number was rolled by the number of rolls to get the percentage.
   - So, if you roll 150 6's out of 1000 rolls, the probability is 15%.
     - Additionally, if I tracked all of the numbers rolled, I could perform the same calculation on each number to get an average between all possible rolls.