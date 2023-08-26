# Manual_Calculator_using_Python
# //////////////////////  Calculator ///////////////////////////////
# Taking Input From User
num_1=int(input("Enter First Number : "))     # Number 1
num_2=int(input("Enter Second Number : "))    # Number 2

# Function For Addition
def Addition(a,b):
    return a+b

# Function For Multiplication
def Multiplication(a,b):
    return a*b

# Function For Division
def Division(a,b):
    return a/b

# Function For Substraction
def Substraction(a,b):
    return a-b

# Taking Input Of Operations From User
oprn=input("Enter any operation that you need (*,/,+,-) : ")

# if-else Statements 
if(oprn=='+'):
    print(f'Sum of {num_1} and {num_2} is : ',Addition(num_1,num_2))
elif(oprn=='-'):
    print(f'Sum of {num_1} and {num_2} is : ',Substraction(num_1,num_2))
elif(oprn=='*'):
    print(f'Sum of {num_1} and {num_2} is : ',Multiplication(num_1,num_2))
elif(oprn=='/'):
    print(f'Sum of {num_1} and {num_2} is : ',Division(num_1,num_2))
else:
    print("You have entered a wrong operation :( ")

# End Of Code
print('Thank You :) ')
