Dynamic programming is a way to solve some problems
In this case we remember the computed result
Where to use it 
When there is subproblems or optimal substructure

Overlapping subproblems - If a problem can be broken into subproblem which can be reused

Example febnocci series

                                          fib(5)
                               fib(4)         +          fib(3)
                        fib(3)    +    fib(2)        fib(2)  +   fib(1)
                   fib(2)  +   fib(1)    
                   
  In above diagram we can see that fib(3) is getting used  Hence reusable subproblem
  
  Optimal substructure - If a problem solution can be constructed from optimal solution of it subproblems
  
  Whole idea of dynamic programming is to store the previous result if required to be used in future to avoid expensive calculation being done again

Memoization - Storing the result of expensive function call and returning the cached result when same input occurs
