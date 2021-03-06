# BobbyBobs

## METHODS:
  We followed the runtimes given by the Java API Subset found [here.](https://www2.cs.duke.edu/csed/ap/subset/doc/ap/ArrayPriorityQueue.html)

  <b> void add(String s) </b> <br> A String is appended to the end of the ArrayPriorityQueue, which has a runtime of O(1). <br><br>
  <b> boolean isEmpty() </b> <br>  Returns whether or not the ArrayPriorityQueue is empty, determined through _size, which has a runtime of O(1). <br> 
  
  <b> String peekMin()</b> <br> Iterates through the ArrayPriorityQueue to find the string of smallest value using .compareTo, which has a runtime of O(n). <br>
  <b> String removeMin() </b> <br> Iterates through the ArrayPriorityQueue to find the string of smallest value using .compareTo, and removing it. This has a runtime of O(n) as well. 

## Belated HEAP TO-DO/DONE List:

1. isEmpty()/peekMin() -- these two methods seem the most easy to implement
2. minChildPos(int) -- this method is a helper function to removeMin, meaning it is essential to the implementation of it
3. toString() -- would help testing
4. removeMin()/add(Integer) -- the central focus of the works
