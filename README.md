# friendly-couscous
s=input('data: ')
l=list(map(int,s.split(',')))
print('list',l)
s=0
for i in l:
    s=s+i
print(s)


l=[]
for i in range(2000,3200):
    if i%7==0 and i%5!=0:
        l.append(i)
print(l)
