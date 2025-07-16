# Codeforces-Problem-158A
Here's a python code for the problem

n,k=map(int, input().split())
arr=list(map(int, input().split()))
s=0
for i in range(len(arr)):
    if arr[i]>=arr[k-1] and arr[i]!=0:
        s+=1 
print(s) 
