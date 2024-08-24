# python-calculator
num1=int(input())
num2=int(input())
operation=input()
if operation == "+":
    print(num1+num2)
elif operation == "-":
    print(num1-num2)
elif operation == "*":
    print(num1*num2)
elif operation == "/":
    print(num1/num2)
else:
    print("give correct operator")
