n=int(input())
c=0
for i in range(1,n):
  if(n%i==0):
    c=c+i
if(c==n):
  print("perfect")
else:
  print("not perfect")
