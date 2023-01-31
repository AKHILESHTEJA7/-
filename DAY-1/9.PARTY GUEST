T = int(input("enter time"))
E=[]
L=[]
for i in range(T):
    e=int(input("number of guests entering"))
    E.append(e)
print(E)
for i in range(T):
    l=int(input("number of guests leaving"))
    L.append(l)
print(L)
Sum=0
Max=0
for i in range(T):
    Sum+=E[i]-L[i]
    Max=max(Sum,Max)
print("maximum number of guests", Max)
