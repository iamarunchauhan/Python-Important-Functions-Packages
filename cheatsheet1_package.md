### 1. heapq
* It will return nlargest and nsmallest numbers from a list

import heapq 
  
votes = [1100, 2500, 3800, 4100, 3420, 9500, 1133, 9887, 9080, 5090]

``` print(heapq.nlargest(3, votes)) ```

[9887, 9500, 9080] 

``` print(heapq.nsmallest(4, votes)) ```

[1100, 1133, 2500, 3420] 

### 2. itertools
* It will merge the multiple sublists into a main list and return the same

import itertools 

l = [['a','b'],['c','d']]

``` print(list(itertools.chain.from_iterable(l))) ```

['a','b','c','d']

### 3. divmod 
* It will return the quotient(a//b) and remainder(a%b) (For Python 3)

a  = 187

b = 10

``` print(divmod(a,b)) ```

(18,7)

### 4. product

from itertools import product

a = [1, 2]

b = [4, 5]

c = [6, 7]

```print(*product(a, b, c))```

(1,4,6) (1,4,7) (1,5,6) (1,5,7) (2,4,6) (2,4,7) (2,5,7)
