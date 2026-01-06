# python-program-14
coding
a=[]
n=int(input("Enter number of elements:"))
for i in range (1,n+1):
    b=int(input("Enter elements:"))
    a.append(b)
    a.sort()
    print("Second largest element is:",a[n-2])
output
Enter number of elements:2
Enter elements:12
Second largest element is: 12
Enter elements:85
Second largest element is: 12
