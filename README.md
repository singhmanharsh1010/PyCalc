# PyCalc
def add(x, y):
    return x + y


def subtract(x, y):
    return x - y


def multiply(x, y):
    return x * y


def divide(x, y):
    return x / y

def square(x):
    return x*x

def square_root(x):
    return x**0.5


print("Select operation.")
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")
print("5.Square")
print("6.Square Root")

while True:
    
    choice = input("Enter choice(1/2/3/4/5/6): ")

    
    if choice in ('1', '2', '3', '4','5','6'):
        if choice == '1':
            num1 = float(input("Enter first number: "))
            num2 = float(input("Enter second number: "))
            print(add(num1, num2))

        elif choice == '2':
            num1 = float(input("Enter first number: "))
            num2 = float(input("Enter second number: "))
            print(subtract(num1, num2))

        elif choice == '3':
            num1 = float(input("Enter first number: "))
            num2 = float(input("Enter second number: "))
            print( multiply(num1, num2))

        elif choice == '4':
            num1 = float(input("Enter first number: "))
            num2 = float(input("Enter second number: "))
            print(divide(num1, num2))
        
        elif choice == '5':
            num1 = float(input("Enter  number: "))
        
            print(square (num1))
        elif choice =='6':
             num1 = float(input("Enter  number: "))
             print(square_root(num1))
        
       
        next_calculation = input("Let's do next calculation? (yes/no): ")
        if next_calculation == "no":
        
          break
    
    else:
        print("Invalid Input")
        
