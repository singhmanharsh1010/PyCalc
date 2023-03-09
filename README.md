print("--------WELCOME TO MY CALC--------")
def add(x,y):
    return x+y
def sub(x,y):
    return x-y
def mul(x,y):
    return x*y
def div(x,y):
    return x/y

print("Choose Your Operation  - \nA)Addition\nB)Subtract\nC)Nultiply\nD)Division")
choice=input("Please enter your choice : \nA\nB\nC\nD\n")
num1=int(input("Enter first number : "))
num2=int(input("ENter second number : "))
if choice=='A':
    print("Your answer is : ",add(num1,num2))
elif choice=='B':
    print("Your answer is : ",sub(num1,num2))
elif choice=='C':
    print("Your answer is : ",mul(num1,num2))
elif choice=='D':
    print("Your answer is : ",div(num1,num2))
else:
    print("Invaloid entry,try again")


