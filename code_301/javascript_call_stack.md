### JavaScript Call Stack

1. What is a ‘call’?

   * Invocation and subsequent excecution of a function
2. How many ‘calls’ can happen at once?

   * One
3. What does LIFO mean?

   * Last in, first out
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
   | stack     |
   | ----------- |
   | function1 |
   | function2 |
   | function3 |
   ```
   function1() {
     //do stuff
   }

   function2() {
    function1()
   }

   function3() {
    function2()
   }

   function3()
   ```
5. What causes a Stack Overflow?

   * A recursive function is called without an exit before the host environment max stack size is exceeded

### References

* [JavaScript Call Stack - Medium](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)
