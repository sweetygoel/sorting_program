# sorting_program

n=int(input("Enter number of elements : "))
print(n)
l=[]
for i in range(n):
    ele=int(input("Enter elements: "))
    l.append(ele)

l.sort()
print(l)
