# username-no-of-attempts-
names={"adi":1111,"siddu":2222,"vicky":3333,"nandu":4444}
username=input("enter the username:")
def name():
    for i in range(3):
        password=int(input("enter the password:"))
        if password==names[username]:
            print("please enter")
            break
        else :
            if (2-i)==0:
                print("blocked")
            else:
                print((2-i),"attempts left")
if username in names.keys():
    name()
else:
    print("no user found")
