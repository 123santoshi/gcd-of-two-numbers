n1=int(input("enter first number===>"))
n2=int(input("enter second number===>"))
minimum=min(n1,n2)
for i in range(1,minimum+1):
    if n1%i==0 and n2%i==0:
        gcd=i
print("gcd of given {0} and {1} is=={2}".format(n1,n2,gcd))