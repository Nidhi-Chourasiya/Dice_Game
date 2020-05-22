import random
n=1
sum=0
while n<=6:
    a=random.randint(1,7)
    n=n+1
    sum=sum+a
    print(a)
print('sum is ', sum)
if sum>=25:
    print('win')
else:
    print('lose')