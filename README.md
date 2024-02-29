# sum-of-natural-numbers in python
#sum of n natural numbers
n=int(input())
s=0
for i in range(n):
  s=s+i
print(s)

# approach-2
n=int(input())
s=0
for i in range(n):
  s=s+i+1
print(s)

# approach-3
n=int(input())
s=0
for i in range(1,n+1):
  s=s+i
print(s)
