The time warden, Ouro Kronii, is a master at time management. She wants to use her time wisely while dating her boyfriend, Mr Tang. There will be $n$ movies shown at the festival. She knows when each movie starts and ends. How can she use her time wisely to watch as many movies as possible? Assuming that the time taken to switch from one movie to another is flowless, means that Kronii can switch to any movie that has not begun right after she had finished the previous movie.

### Input format
The first line consists of $1$ integer, $T$, as the number of test cases.
After that, in the first line of each test case consists of $1$ integer, $n$, as the total number of movies.<br>Next, there are $n$ lines of integer pairs, $s$ and $e$, which is the the starting and ending times of a movie.

### Constraints
- $1 \le n \le 10^{4}$
- $1 \le s_i \lt e_i \le 24,(1 \le i \le n)$

### Output format
The output needs to be in:
> `Case #i: l`<br> Where $i$ is the number of test case and $l$ is the maximum number of movies.

<div style="page-break-after: always;"></div>

### Example
#### Sample Input 
```
2
3  
3 5  
4 9  
5 8
2
1 10
1 6
```

#### Sample Output
```
Case #1: 2
Case #2: 1
```

#### Explanation
In the first test case, she can watch $2$ movie since the first movie starts at $3$ and ends at $5$, the third movie starts at $5$ and ends at $8$.<br>Similarly, in the second test case, she can only watch one of the movies since the first movie starts at $1$ and ends at $10$ while the second movie starts at $1$ and end at $6$, she cannot watch a movie that has already begun.
