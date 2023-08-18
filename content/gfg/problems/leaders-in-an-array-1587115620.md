---
title: "leaders-in-an-array-1587115620"
number: "-"
difficulty: "easy"
date: 2023-08-18T20:53:43+05:30
draft: false
---

Iterate from the right end of the array.  
If the current element is larger than the lastMaxi.  
then there is no element to its right which is larger than the current element,  
so add it to the res array. Update lastMaxi.


{{< code name="p1.cpp" start=35 num=19 >}}
