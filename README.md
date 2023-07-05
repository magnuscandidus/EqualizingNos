# EqualizingNos
# cook your dish here
t=int(input())
while t:
    a,b=map(int,input().split())
    if(abs(a-b)%2==0):
        print("YES")
    else:
        print("NO")
    t-=1
