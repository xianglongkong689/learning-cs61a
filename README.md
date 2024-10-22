# learning-cs61a
recording the progress of learning cs61a

## lab 01 Functions,control
### review:
#### common ways to run codes
1. *no command*:using terminal test the code:run code(*python filename*),you will see no output unless there is a syntax error.
2. *-m*:doctest(文件测试)(*python -m doctest filename*)(when doc passed the test, no output displayed.otherwise,failed information displayed).
3. *-i*:run the codes and open a interactive session.
#### ok
using ok test the function(*python ok -q FUNCTION*(函数名字，用大写替代))if your code contains a call to print that start with DEBUG:,this will be ignored.
#### division-related operactors
- **/** true division 5/2=2.5
- **//** floor division 5/2=2
- **%** modulo 5%2=1
> **zerodivisionerror** occur when dividing by 0
#### return and print
- executes *return* statement terminates immediately
- executes print not

### What Would Python Display?(WWPD)
#### Q1 WWPD:Control
```python
>>> def xk(c, d):
...     if c == 4:
...         return 6
...     elif d >= 4:
...         return 6 + 7 + c
...     else:
...         return 25
>>> xk(10, 10)
______23
>>> xk(10, 6)
______23
>>> xk(4, 6)
______6
>>> xk(0, 0)
______25


>>> def how_big(x):
...     if x > 10:
...         print('huge')
...     elif x > 5:
...         return 'big'
...     if x > 0:
...         print('positive')
...     else:
...         print(0)
>>> how_big(7)         # A returned string is displayed with single quotes
______'big'
>>> print(how_big(7))  # A printed string has no quotes
______big
>>> how_big(12)
______huge
positive
>>> print(how_big(12))
______huge
positive
None
>>> print(how_big(1), how_big(0))
______positive
0
None None


>>> n = 3
>>> while n >= 0:
...     n -= 1
...     print(n)
______2
1
0
-1


>>> negative = -12
>>> while negative:  # All numbers are true values except 0
...    if negative + 6:
...        print(negative)
...    negative += 3
______-12
-9
-3
```

#### Q2 Debug Quiz

### Write code
#### Q3 Falling factorial
Write a code that takes two arguement n and k, return conduct of k consecutive numbers starts with n and working downward. when k = 0, return 1.

#### Q4 Dvisible by k
Write a function that takes two arguments n and k. It print all positive interges less than or equal to n that divisible by k.Then, return how many number printed.

#### Q5 Sum digits
Write a function takes a nonnegative integer and sums its digits.

#### Q6 WWPD

#### Q7 Double eights
Write a function takes a number and determines if contain two adjacent 8
