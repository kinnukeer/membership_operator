# membership_operator
n=int(input())
r=list(map(int,input().split()))
a=[]
for i in range(n):
  if r[i] not in a:
    a.append(r[i])
print(a)
'''
n=int(input())
r=list(map(int,input().split()))
a=[]
for i in r:
  if i not in a:
    a.append(i)
print(a)
