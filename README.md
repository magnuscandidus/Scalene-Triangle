# Scalene-Triangle
for _testcase in range(int(input())):
    a,b,c = map(int,input().split())
    if a == b or a == c or b == c: print("NO")
    else: print("YES")
