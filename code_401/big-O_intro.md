### Intro to Big-O

##### After reading “Beginners Guide to Big O,” explain the concept of time complexity and space complexity.

- Big O describes how an algorithm's performance changes as the input size changes. It tells us how much time an algorithm needs or how much memory it uses
  - O(1) means the algorithm's time or space stays the same regardless of input size
  - O(N) means the time or memory use grows linearly with the input size, meaning more data = more time
  - O(N²) or O(2^N) indicate that as the input grows, the time or memory use increases much faster, which can be a problem for large data
  - O (2^N) grows exponentially, so it starts off fairly level, but grows very rapidly with each iteration
  - O(log N), like binary search, means the algorithm gets faster as the data size grows, making it efficient for big datasets. It grows quickly at the beginning, but levels off as it increases
- This concept can help choose the right algorithms appropriate for each different task and data set