a=int(input())
for i in range(a):
    b=input().split(" ")
    c=int(b[0])
    d=int(b[1])
    count1=0
    count2=0
    for i in range(c):
        g=input()
        for n in range(d):
            o=i+n
            if o%2==0:
                if g[n]=="G":
                    count1+=3
                else:
                    count2+=5
            else:
                if g[n]=="G":
                    count2+=3
                else:
                    count1+=5
    op1=min(count1,count2)
    #opn=min(count2)
    print(op1)
    #print(op2)
                    
