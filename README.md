# fibonacci-using-functions
def fib(n):
    fib_s=[]
    a,b=0,1
    for i in range(n):
        fib_s.append(a)
        a,b=b,a+b
    return fib_s
   
n=int(input())
print(fib(n))
