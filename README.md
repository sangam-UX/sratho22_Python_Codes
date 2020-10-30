# sratho22_Python_Codes
This Repository will contain usefull python code using basic and advance concept
# Faulty calculater
# Design a calculater which will perform all calculation correctly except following

# 145*3 =555, 56+19=77, 56/4 =100


input1 = int(input("Enter 1st input from user: "))
operator = input("Enter operator from user: ")
input2 = int(input("Enter 2nd input from user: "))

if operator=="*":
    if input1 == 145 and input2 == 3:
        print(555)
    else:
        print(input2*input1)
elif operator == "+":
    if input1 == 56 and input2 == 19:
        print(77)
    else:
        print(input1+input2)
elif operator == "/":
    if input1 == 56 and input2 == 4:
        print(100)
    else:
        print(input1/input2)
