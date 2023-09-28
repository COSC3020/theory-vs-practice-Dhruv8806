[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11977131&assignment_repo_type=AssignmentRepo)
# Theory vs. Practice

- List 3 reasons why asymptotic analysis may be misleading with respect to
  actual performance in practice.

   ->  It ignores constants that can be significant. 

   ->  Asymptotic doesn’t work well with for small input sizes, and therefore $n_0$ would be ignored. 

   ->  The asymptotic analysis does not provide an exact running time.


- Suppose finding a particular element in a binary search tree with 1,000
  elements takes 5 seconds. Given what you know about the asymptotic complexity
  of search in a binary search tree, how long would you guess finding the same
  element in a search tree with 10,000 elements takes? Explain your reasoning.

  -> Given that finding a particular element in a binary search tree with 1,000 elements takes 5 seconds, we can estimate the running time of finding the same element in 
 a search tree with 10,000 elements as follows:

    T(10000) = $\frac{5*log(10000)}{log(1000)}$

    T(10000) = 6.667 seconds

  -> Therefore, we could estimate that finding a particular element in a binary search tree with 10,000 elements would take about 6.67 seconds.


- You measure the time with 10,000 elements and it takes 100 seconds! List 3
  reasons why this could be the case, given that reasoning with the asymptotic
  complexity suggests a different time.

  -> The amount of input memory available can affect the performance of an algorithm. If the input data is too large to fit in memory, the algorithm will need to access the hard drive to read and write data, which can slow it down.
  
  -> The algorithm’s efficiency can be slow if it is not coded in the most efficient way. It could be due to using wrong data structures, coding in a complex way, unbalanced tree or it could be the input data being used.
  
  -> The hardware and software platform could be slow. The hardware and software platform on which the algorithm is running can also have a significant impact on its performance.  Such as the CPU speed or the operating performance. 


Add your answers to this markdown file.


  -> Sources used: 
  
     - Discussed with TA in lab time
     
     - https://www.geeksforgeeks.org/asymptotic-notation-and-analysis-based-on-input-size-of-algorithms/
     
     - https://en.wikipedia.org/wiki/Algorithmic_efficiency
     
     - https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/running-time-of-binary-search
