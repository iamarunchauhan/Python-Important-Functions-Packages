### 1. heapq

import heapq 
  
votes = [1100, 2500, 3800, 4100, 3420, 9500, 1133, 9887, 9080, 5090]

>> print(heapq.nlargest(3, votes)) 

[9887, 9500, 9080]

>> print(heapq.nsmallest(4, votes))

[1100, 1133, 2500, 3420]
