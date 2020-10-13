### LRU cache	
HashMap with doubly linked list.  OR.         LinkedHashMap

### Rotate matrix	
reverse upside down and then swap with diagonally opposite cells

### kth smallest or largest integer	
1.sort & then traverse.     
2.Priority Queue with limit ( A min heap / max heap implementation by java )
TC: O(Nlogk). logk is constant

### islands, floodfill	
1. DFS drown/mark

### battleships	
1.same as island (in place).                        
2.count heads only (no mutation)

### island perimeter	
islands x4 - neighbor x2

### Floyd warshall distances	
Dij = min(Dij ,Dik + Dkj)

### can course be completed given pre reqs	
floyd warshal variant

### why is recursion 0(2^n)
for every call you have 2 more calls. So if levels are 3, we have 2^0+ 2^1 + 2^2 = 7 = 2^3  - 1 

### number of paths in matrix	
dp[i][j] = dp[i-1][j] + dp[i][j-1] 
i.e 
current = left + top.       
DO NOT do this recursively, lol

### palindromic substring
expand palindrome 
Steps: 
- start with one letter (i=j) or 2 adjacent letters (j-i = 1)
- i--, j++

### Longest valid parentheses
- stack
  insert indices of '('
- DP
  s : [( ,) ,( ,( ,) ,) ]
  DP:[0,2,0,0,2,6]
  
## Also check [the ppt here](https://www.linkedin.com/posts/jayati-tiwari_data-strucutre-problem-solving-techniques-activity-6684391136074715137-z80V/) for different approaches to use for solving problems of different categories