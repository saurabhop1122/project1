# project1
def fib():
    list=[]
    noOfInput = int(input("How many numbers you want to enter?"))
    for i in range(0,noOfInput):
        element=int(input("Enter the number:"))
        list.append(element)
    maxNo = max(list)
    n1,n2=0,1
    list1=[0]
    if maxNo <= 0:
        print("0 is valid or negative")
    elif maxNo==1:
        list1.append(n1)
