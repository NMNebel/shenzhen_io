



```
if x0 == 1 and p1 == 100:
    p1 = 0
```

```
teq x0 1
+ teq p1 100
+ mov 0 p1
```



```
mov p0 50
tcp x0 1
+ mov p0 100
- mov p0 0
```

```
p0 = 50
if x0 == 1:
    p0 = 100
else:
    p0 = 0
```

