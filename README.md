# learning-cs61a
recording the progress of learning cs61a

## lab 01 Functions,control
### review:
#### common ways to run codes
1. *no command*:using terminal test the code:run code(*python filename*),
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
