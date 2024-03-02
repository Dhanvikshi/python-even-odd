# python-even-odd
#problem-1--even number index sum
#approch-1
'''n=int(input())
a=list(map(int,input().split()))
res=0
for i in range(n):
  if a[i]%2==0:
    res = res + i
print(res)'''

#pro--1--with range
#appr--1
'''n=int(input())
a=list(map(int,input().split()))
r=0
for i in range(n):
  if a[i]%2==0 and a[i]>r:
    r=a[i]
print(r)'''
