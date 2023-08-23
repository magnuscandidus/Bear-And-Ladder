# Bear-And-Ladder
for i in range(int(input())):
    a,b=map(int,input().split())
    if(max(a,b)-min(a,b)==2):
        print("YES")
    elif((min(a,b)%2==1 and max(a,b)-min(a,b)==1)):
        print("YES")
    else:
        print("NO")
