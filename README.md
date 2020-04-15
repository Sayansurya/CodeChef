# CodeChef
# cook your dish here

t=int(input())
while t>0:
    n=int(input())
    if n==1:
        print(1)
        print(1,1)
    else:
        print(n//2)
        if n%2!=0:
            print(3,1,2,n)
            for i in range(3,n-1,2):
                print(2,i,i+1)
                
        else:
            print(2,1,n)
            for i in range(2,n-1,2):
                print(2,i,i+1)
    t=t-1
