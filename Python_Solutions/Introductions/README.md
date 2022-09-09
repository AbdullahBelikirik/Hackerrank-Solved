# [HackerRank Python Solutions - Introduction](https://www.hackerrank.com/domains/python?badge_type=python&filters%5Bsubdomains%5D%5B%5D=py-introduction "Python - Introduction")

### [Say "Hello, World!" With Python](https://www.hackerrank.com/challenges/py-hello-world/problem?isFullScreen=true "Say 'Hello, World!' With Python")

```py
print("Hello, World!")
```

### [Python If-Else](https://www.hackerrank.com/challenges/py-if-else/problem?isFullScreen=true "Python If-Else")

```py
if n%2 == 1:
    print("Weird")
else:
    if 2<=n<=5:
        print("Not Weird")
    elif 6<=n<=20 :
        print("Weird")
    elif n>20 :
        print("Not Weird")
```

### [Arithmetic Operators](https://www.hackerrank.com/challenges/python-arithmetic-operators/problem?isFullScreen=true "Arithmetic Operators")

```py
print(a+b)
print(a-b)
print(a*b)
```

### [Write A Function](https://www.hackerrank.com/challenges/write-a-function/problem?isFullScreen=true "Write A Function")

```py
def is_leap(year):
    leap = False
    if year&4 == 0:
        leap = True
    return leap
```

### [Python: Division](https://www.hackerrank.com/challenges/python-division/problem?isFullScreen=true "Python: Division")

```py
print(a//b)
print(a/b)
```

### [Loops](https://www.hackerrank.com/challenges/python-loops/problem?isFullScreen=true "Loops")

```py
for i in range(n):
    print(i*i)
```

### [Print Function](https://www.hackerrank.com/challenges/python-print/problem?isFullScreen=true "Print Function")

```py
for i in range(n):
    print(i+1, end = '')
```