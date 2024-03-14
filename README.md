# largest-among-three-numbers
a = int(input())
b = int(input())
print(a+b)
'''
'''
a,b=map(int,input().split())
print(a+b)
'''
'''
a,b=map(int,input().split("#"))
print(a+b)
'''
# Problem - 1(1st largest among two numbers)
'''
a = int(input())
b = int(input())
if a > b:
    print(a)
else:
    print(b)
'''
# Problem - 2(1st largest among three numbers)
'''
a,b,c = map(int,input().split())
if a>b and a>c:
    print(a)
elif b>c:
    print(b)
else:
    print(c)
'''
# Problem - 3(2nd largest among three numbers)
'''
a,b,c = map(int,input().split(","))
if a>b and a>c:
    a = 0
elif b>c:
    b = 0
else:
    c = 0
if a>b and a>c:
    print(a)
elif b>c:
    print(b)
else:
    print(c)
'''
