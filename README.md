# SimpleCalculator
def calculator(op,x, y):
    if op=='+':
        return x+y
    elif op=='-':
        return x-y
    elif op=='*':
        return x*y
    elif op=='/':
        return x/y
    elif op=='%':
        return x%y
    elif op=='**':
        return x**y
    else:
        return "Invalid operation"
        
print("Welcome to Simple Calculator")
print("Operations that can be performed:")
print("1.Add")
print("2.Subtract")
print("3.Multiply")
print("4.Divide")
print("5.Mod")
print("6.Power")

while True:
    a=int(input("Enter the first number:"))
    b=int(input("Enter the second number:"))
    op=input("Enter the operator:")
    output=calculator(op,a,b)
    print(output)
    print(calculator)
