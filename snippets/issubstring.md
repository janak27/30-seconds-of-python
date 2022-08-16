---
title: Checking the substring
tags: string
expertise: beginner
firstSeen: 2022-08-16 15:11:00 -0400
---

Identifying the substring `s1` in `s2` string.

- We are simply using library functions of `string`.
- The function itself iterate through both strings and trying to find out common patterns.
- Here the function is matching string `s1` to the `s2`. 

```py
def issubstring(s1, s2):
    if s1 in s2:
        print(s2.index(s1))
        return s2.index(s1)
    else:
        print("not present")
        return -1
```

```py
issubstring("code","30secondsofcode") #11
issubstring("red","blue") #not present
issubstring("ana","janak")#1
```
