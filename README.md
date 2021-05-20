# assignment1.py
#its a faulty calculator
print("Welcome to the Calculator program")

var1 = int(input("enter ur first number\n"))
var2 = int(input("enter ur second number\n"))
opp = input("enter \n1 -> *\n2 -> +\n3 -> -\n4 -> / \n")
if(opp == "1"):
    if(var1 == 45 and var2 == 3):
        print("45 * 3 = 555")
    else:
        print(f"{var1} * {var2} = {var1*var2}")

elif(opp == "2"):
    if(var1 == 56 and var2 == 9):
        print("56 + 9 =77")
    else:
        print(f"{var1} + {var2} = {var1+var2}")
elif(opp == "4"):
    if(var1 == 56 and var2 == 6):
        print("56 / 6 = 4")

    else:
     print(f"{var1} / {var2} = {var1 / var2}")
elif(opp == "3"):
    print(f"{var1} - {var2} = {var1-var2}")
else:
    print("Try again with a vadil operator")
print("thank you for using")
