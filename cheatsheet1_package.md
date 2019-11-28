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
