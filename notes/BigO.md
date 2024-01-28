

## What is Asymptotic Notation 

* A mathematical notation used to express how the execution time or other computational resource usage of an algorithm behaves as the input size increases.
* The comparison and evaluation of algorithms' efficiency can be done independently of external conditions such as hardware or software environments.

## Terms of asymptotic notation


* Algorithm does not guarantee consistent execution times. therefore, we consider the best case, worst case, and average case scenarios to evaluate its performance.

* O(n)
  * linear time
  * count the number of operations
* O(1)
  * constant time 
* O(n^2)
* O(log n)
  * binary search
  * example
    * bad case  
      * size 8 -> 3operations (log2^8)
      * size 16 -> 4operations (log2^16)
* Ω(1)
  * no matter how big the input is, it find it quickly
  * example
    * best case 
      * size 8 -> 1operations
      * size 16 -> 1operations
* Θ
  * best case and worst case are the same
  * Ω(1) == O(1) 