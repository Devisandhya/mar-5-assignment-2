# mar-5-assignment-2
n=int(input())
l=input().split()
t=[]
for i in l:
    t.append(int(i))
x=[]
for i in t:
    if i not in x:
        x.append(i)
x.sort(reverse=True)
print(x[2])
