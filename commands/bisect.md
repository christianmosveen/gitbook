# Bisect
Do a binary search through the commit history to find the commit that introduced a bug

```
git bisect start <bad> <good>
git bisect run <command>
```

#### Assignments
1. Let bisect go through all the commits to find out in which commit a specific file was added (bad = HEAD, good = <first commit>). Possible command: ```[ ! -f <file> ]```.
