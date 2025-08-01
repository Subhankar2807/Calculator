# Calculator
A short Python program of Calculator

Value1 = (float(input("Enter the First Number:")))

Operation = input("Enter the Calculation Operation:")

Value2 = (float(input("Enter the Second Number:")))


if Operation == "+":
    print(Value1 + Value2)
elif Operation =="-":
    print(Value1 - Value2)
elif Operation =="*":
    print(Value1 * Value2)
elif Operation =="/":
    print(Value1 / Value2)

else:
    print("Calculation Error")
