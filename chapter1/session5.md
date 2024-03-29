# 1.5-算法分析

1. 第一次尝试的算法核心部分

```python
for a in range(0, 1001):
    for b in range(0, 1001):
        for c in range(0, 1001):
            if a**2 + b**2 == c**2 and a+b+c == 1000:
                print("a, b, c: %d, %d, %d" % (a, b, c))
```

 **时间复杂度：**

T\(n\) = O\(n\*n\*n\) = O\(n3\)

1. 第二次尝试的算法核心部分

```python
for a in range(0, 1001):
    for b in range(0, 1001-a):
        c = 1000 - a - b
        if a**2 + b**2 == c**2:
            print("a, b, c: %d, %d, %d" % (a, b, c))
```

 **时间复杂度：**

T\(n\) = O\(n\*n\*\(1+1\)\) = O\(n\*n\) = O\(n2\)

**由此可见，我们尝试的第二种算法要比第一种算法的时间复杂度好多的。**

