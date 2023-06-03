The rascal, Sakuta Azusagawa is superstitious. He has long admired his senior Mai Sakurajima. Today, he finally decided to date his senior. He chooses a romantic movie *Suzume*, and he plans to confess to his senior right after the movie ends. Unfortunately, he failed, blaming the serial number on the ticket. He believes that a **"lucky ticket"** should have at least $5$ consecutive numbers that do not repeat. <br>Your task is to help him to find the lucky ticket.

### Input format
The first line consist of $1$ integer, $n$, as the total number of ticket.<br>
Next, there are $n$ line of integer, $T$, which is the serial number of ticket.

### Constraints
- $1 \le n \le 10^{4}$
- $1 \le T_i \le 10^{6},(1 \le i \le n)$

### Output format
Output the length of the longest substring without repeating characters and determine whether it is a lucky ticket or not.
The output needs to be in:
> `Ticket #i: l, t` <br>
> Whereas $i$ is the $i^{th}$ ticket (starts from $1$), $l$ is the the length of the longest substring without repeating characters, $t$ is whether the ticket is lucky (`T`) or not (`F`).

### Example
#### Sample Input 
```
3
12345
182819
1234567891234
```

#### Sample Output
```
Ticket #1: 5, T
Ticket #2: 4, F
Ticket #3: 9, T
```

#### Explanation
The first ticket has $5$ non repeating characters, which are $\{1,2,3,4,5\}$. Therefore, it is a lucky ticket. <br>Similarly, the second ticket has $4$ non repeating characters, which are $\{2,8,1,9\}$. Therefore, it is not a lucky ticket. <br>So as the last ticket is true since it has $9$ non repeating characters, which are $\{1,2,3,4,5,6,7,8,9\}$. Therefore, it is a lucky ticket.
