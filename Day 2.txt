1.print(2+2) #4
print("2"+"2") #22
val1=int(input("Enter first value:")) #2
val2=int(input("Enter second value:")) #2
print(val1+val2) #22

2.#int() used to convert in integer
print(int(3.14))
#print(int(10+5j))
print(int(True))#=1
print(int(False))#=0
#print(int("4.22"))
print(int("4"))
print(str("srushti"))

3.#float() used to convert
print(float(3))#3.0
#print(float(50+2j))
print(float(True))#=1.0
print(float(False))#=0.0
print(float(4.22))
print(float("4"))

4.bool() is used to convert
print(bool(0)) 
print(bool(15))
print(bool(3.14))
print(bool(1+2j))
print(bool(0+0j))
print(bool(-1))
print(bool(False))
print(bool(True))
print(bool(" "))

5.#WAP to accept
n=int(input("Enter any single digit:"))
if n>0:
    print("positive number")
if n<0:
    print("negetive number")
if n==0:
    print("zero")
        
6.#WAp to accept 5 numbers in 5 different variables and check max number and input
n1=int(input("Enter the value of n1:"))#6
n2=int(input("Enter the value of n2:"))#5
n3=int(input("Enter the value of n3:"))#4
n4=int(input("Enter the value of n4:"))#2
n5=int(input("Enter the value of n5:"))#1
if n1>n2 and n1>n3 and n1>n4 and n1>n5:
    print("N1 is max value")
if n2>n1 and n2>n3 and n2>n4 and n2>n5:
    print("N2 is max value")
if n3>n1 and n3>n2 and n3>n4 and n3>n5:
    print("N3 is max value")
if n4>n1 and n4>n2 and n4>n3 and n4>n5:
    print("N4 is max value")
if n5>n1 and n5>n2 and n5>n3 and n5>n4:
    print("N5 is max value")

7.#WAP to accept the three paper marks and calculate total,percentage and if percentage is greater than or equal to 60 so he/she is eligible for placement drive
math=int(input("Enter marks of Maths:"))#70
chem=int(input("Enter marks of chem:"))#80
phy=int(input("Enter marks of phy:"))#90
total=phy+chem+math
percentage=total/3.0
print("Total =",total)
if percentage>=60:
    print("You are eligible for placement drive")
else:
    print("You are not eligible for placement drive")

8.#WAP to accept the three paper marks and calculate total,percentage and if percentage is greater than or equal to 60 so he/she is eligible for placement drive
math=int(input("Enter marks of Maths:"))
chem=int(input("Enter marks of chem:"))
phy=int(input("Enter marks of phy:"))
total=phy+chem+math
percentage=total/3.0
print("Total =",total)
print("Percentage=",percentage)
if percentage>=60:
    print("You are eligible for placement drive")
else:
    print("You are not eligible for placement drive")

9.#WAP to calculate simple interest
pa=int(input("Enter principal amount:"))#100000
roi=int(input("Enter rate of interest:"))#10
time=int(input("Enter the loan  amount duration:"))#1
si=pa*roi*time/100
print("Simple interest=",si)

10.#WAP to enter height of user in feet and convert it into inch and centemeter
height=float(input("Enter the height of user in feet:"))#5.5
inch=height*12#we get the value of inch
cm=inch*2.54
print("inch=",inch)
print("centemeter=",cm)

11.#WAP to take centigrade temperature and convert it into fahrenheit temperature 
centi=float(input("Enter the centigrade temperature:"))#26.5
f=1.8*centi+240
print("Fahrenheit=",f)

12.#Slicing string
name="prashantjha"
#indexing=012345678910
print(name[0])#p
print(name[1])#r
print(name[-1])#a
#print(name[15]) Error string index out of range
print(name[0:5])#end-1,5-1=4,prash
print(name[1:])#rashantjha
print(name[:5])#5-1=4 prash
print(name[:])#prashantjha
print(name[1:8:2])#'''8-1=7=rsat
print(name[::-1])#ahjtnahsarp

13.s="help4code is best platform for practicinh programming"
print(s.find("help4code"))
print(s.find("python"))
print(s.find("programming"))
#find() return the starting index no of string if it is found else if the string not found so it return -1

14.#Join fun
s="Shreya","Srushti","Priya"
m='|'.join(s)
print(m)

15.
s="Python is High level programming Language"
print(s.lower())
print(s.upper())
print(s.swapcase())
print(s.title())
print(s.capitalize())

16.
phy=50
chem=60
math=70
print("physics={} chemistry={} Math={}".format(phy,chem,math))
print("physics={0} chemistry={1} Math={2}".format(phy,chem,math))
print("physics={x} chemistry={y} Math={z}".format(x=phy,y=chem,z=math))
total=phy+chem+math
print("Toatal Marks",f"{total}")
print("Roll No=","7".zfill(4))

17.BODMAS
a=50
b=30
c=20
d=10
print((a+b)*c/d)#160
print((a-b)*(c/d))#40
print(a+(b*c)/d)#110
    
GitHub:-
create repository:
day1-
day2-

