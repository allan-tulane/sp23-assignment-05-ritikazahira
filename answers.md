# CMPS 2200 Assignment 5
## Answers

**Name:**_________________________


Place all written answers from `assignment-05.md` here for easier grading.





- **1a.**
The greedy algorithms we could use is the largest denomination first algorithm, where all the coins with the largest denomination are taken and we do this process taking the next largest denomination until we produce as few coins as possible that sum to N. 
The work and span of this algorithm is O(log N) because as we go down N domination reduces by 2 (and since we are repeadely dividing the number of iterations is log). 





- **2b.**
A. the greedy algorithm cannot work optimally because for example what if we had coin demoniations of 1, 7, and 10 and change for N=15. It would pick one coin of 10 and 5 coins of 1 however, the optimal solution is 2 coins of 7. 


The optimal substructure is C(N,K) = min{C(N, k-1), 1 + C(N- r, k). r is the coins of denomination to k numbers. The work and span is O(Nk). The work is O(Nk) is because we need to consider the minimum number of coins for each amount form 1 to N and also see the denomination and the span is )(n*K) because the result is based on the previous results. 
- **3a.**


in main.py



- **3b.**



in main.py


- **3c.**


in main.py
