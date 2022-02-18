# 18-02-22-ass-2
#write a program to print sum of n factorial
n=int(input('enter number:'))
f=1
sum=0
for i in range(1,n+1):
    f=f*i
    sum=sum+f
print(sum)

output:
enter number:8
46233
