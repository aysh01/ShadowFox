import random as rd
x="abcdefghijklmnopqrstuvwxyz"

#r=rd.randint(0,len(x)-1)
guess=[]
for i in range(0,5):
    r=rd.randint(0,len(x)-1)
    guess.append(x[r])
print(guess)
x=0
y=[]
for i in range(0,len(guess)):
    y.append("-")

def display():
    try:
        x=input("Guess the Word..?\n").lower()
        while i in range(1,len(guess)):
            if len(x)!=1:
                print("Only one character allowed")
                break
            if x in guess:
                for j in range(0,len(guess)):
                    x=input("Guess Again..\n").lower()
                    if guess.index(x)==guess.index(x):
                        y[guess.index(x)]=x
                    print(y)  
                break
            if x not in guess:
                print("Try again..")
                break

    except Exception as e:
        print(e)
display()
