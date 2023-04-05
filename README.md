# Demo2
# branching statements
# if statement
n=int(input("enter a number"))
if n>10:
    print("two digit numbers")
print("single digit number")
# if else statement
a=int(input("enter the age"))
if a>=18:
    print("adult")
else:
    print("child")
# elif statement
marks=int(input("enter the marks"))
if marks>=90:
    print("distinction")
elif marks>=70:
    print("first class")
elif marks>=60:
    print("second class")
else:
    print("fail")

#nested if statement
rate=int(input("rate of the product"))
quantity=int(input("quantity of the product"))
if rate>=300:
    if quantity>=5:
        print("the product is of more quantity")
    else:
        print("the product is of less quantity")
else:
    print("the product is of low range and less quantity")
# iterative statements
for i in range(10,20,2):
    print(i)
    i=i+1
# while loop
i=1
while i<=5:
    print(i*4)
    i=i+1
# transfer statement
# break statement
for i in range(20):
    print(i)
    if i==12:
        break
#  continue statement
for i in range(5):
    if i==3:
        continue
    print(i)



      
