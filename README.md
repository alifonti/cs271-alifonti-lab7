# Questions

**Question 1**

*(What is the purpose of the various auxiliary methods populateList, populateFifoList, and ReverseLines.printReverse?)*

- To allow a recursive implementation of these methods without requiring to enter the arguments used in the recursive method.

**Question 2**

*(Why do these methods need to have arguments, and how does the argument change from one recursive call to the next?)*

- To allow the method to progress through the stack or lines instead of repeating the same calculations.

**Question 3**

*(What are the time and space complexity of each of the populateList populateFifoList methods, as well as ReverseLines.printReverse?)*

- The complexity of `populateList` and `populateFifoList` are O(n), and `ReverseLines.printReverse` is O(n), too.

**Question 4**

*(Which of these methods can be implemented using while loops?)*

- Both `populateList` and `populateFifoList` can be implemented using loops.