# Calculator-
This Python calculator program performs basic arithmetic operations: addition, subtraction, multiplication, and division. It displays a menu, accepts the user's choice and two numbers, performs the selected operation, and shows the result. It also includes an option to stop the program and handles invalid choices.      
print("""
1. Addition
2. Substraction
3. Multiplication
4. Divion
5. Stop
""")

choice = int(input("Enter what's your choice"))
if choice==5:
    print("Stopping the program :")
elif choice in [1, 2, 3, 4]:
    num1 = int(input("Enter first number"))
    num2 = int(input("Enter second number"))

if choice==1:
    print("Addition is :", num1+num2)
elif choice==2:
    print("Substraction is :", num1-num2)
elif choice==3:
    print("Multiplication is :", num1*num2)
elif choice==4:
    print("Divion is :", num1/num2)
else:
    print("Enter correct choice")
