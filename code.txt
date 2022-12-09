op = input("Operation:")
import math
while(op!="exit"):
    if(op=="square root" or op=="root"):
        num=float(input("Number:"))
        print("Square root of",num,"is:",math.sqrt(num))


    elif(op=="sine" or op=="sin"):
        num = float(input("Degree:"))
        print("Sine(",num,"):",math.sin(math.radians(num)))


    elif(op=="cosine" or op=="cos"):
        num = float(input("Degree:"))
        print("Cosine(",num,"):",math.cos(math.radians(num)))


    elif(op=="tangent" or op=="tan"):
        num = float(input("Degree:"))
        print("Tangent(",num,"):",math.tan(math.radians(num)))

    elif(op=="radian"):
        num = float(input("Degree:"))
        print("Radian:",math.radians(num))


    elif(op=="degree"):
        num = float(input("Radian:"))
        print("Degree:",math.degrees(num))


    elif(op in ["add","+","sum"]):
        num1=float(input("number1:"))
        num2=float(input("number2:"))
        print("Addition:",num1+num2)


    elif(op=="sub" or op=="-"):
        num1 = float(input("number1:"))
        num2 = float(input("number2:"))
        print("Subtraction:",num1-num2)


    elif(op=="multiply" or op=="x"):
        num1 = float(input("number1:"))
        num2 = float(input("number2:"))
        print("Multiplication:",num1*num2)


    elif(op=="divide" or op=="/"):
        num1 = float(input("number1:"))
        num2 = float(input("number2:"))
        print("Division:",num1/num2)


    elif(op=="mod" or op=="%"):
        num1 = float(input("number1:"))
        num2 = float(input("number2:"))
        print("Modulus division:",num1//num2)


    elif(op=="exponent" or op=="power"):
        num1 = float(input("Base:"))
        num2 = float(input("Power:"))
        print("pow(",num1,",",num2,"):",num1**num2)

    else:
        print("Invalid Operation")

    print()
    op = str(input("Operation:"))


print("THANK YOU")
