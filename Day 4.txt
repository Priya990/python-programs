Day 3
1.#Using Count method
n=[1,2,3,5,5,5,1,2,4,4,6,6,6]
print(n.count(1))
print(n.count(2))
print(n.count(3))
print(n.count(4))
print(n.count(5))
print(n.count(6))
print(n.count(7))

2.#using val.index method
val=[1,2,3,5,5,5,1,2,4,4,6,6,6]
print(val.index(1))
print(val.index(2))
print(val.index(3))
print(val.index(4))
print(val.index(5))
print(val.index(6))

3.#Comparing the address
x=['A','B','C']
y=['A','B','C']
z=[1,2,3,4]
print(x==y)
print(x==z)
print(x!=z)

4.#Using Datetime
import datetime
#datetime formatting
date=datetime.datetime.now()
print("It's now:{:%d/%m/%Y %H:%M:%S}".format(date))

5.#Break() function 
for i in range(1,5): #i=3
    if i==3:
        break
    print(i)

6.#Continue() function
for i in range(1,5): #i=3
    if i==3:
        continue
    print(i)

7.#Continue() function
mycart=[10,20,200,300,800,60,700]
for i in mycart:     #i=1:20
    if i>400:
        print("This my purchased cart item")
        continue
    print(i)

8.#important question
list=[1,2,3,4,5,6,7,8,9,10]
sum=0   #sum=1,2,3,4,5,6,7,8,9,10
for x in list: #x=0:1
    sum=sum+x
print("The Sum=",sum)

Ans:1+2+3+4+5+6+7+8+9+10=55

9.#Break() function
rollno=[3,5,7,1,11,4,5,2]
for x in rollno:
    if x==2 or x==4 or x==6 or x==8 or x==10:
        print("even no is found",x)
        break
Ans:4
*if take continue function then its ans is 4 and 2

10.
name="srushtia"
     #01234567
for i in name:  #i=0
    print(i)

11.#WAP to remove duplicate characters
name="Prashant"
newname=" "#
for i in name:  #i=1:s
    if i not in newname:
        newname +=i
    print(name)
    print(newname)

12.
name="prashant"
i=0
for x in name: #x=1:p
    if x=='n':
        print("The character present at index no",i,"value=:",x)
        break
    i=i+1  #update by one

13.#counting vowels and consonents
name="prashant"
vow=0
cons=0
vowels=['a','e','i','o','u']
for i in name: #x=1:p
    if i in vowels:
        vow+=1
    else:
        cons+=1
print("vowels=",vow)
print("consonent=",cons)

14.#WAP to calculate factorial of 5!
num=5
fact=1
for i in range(1,num+1):
    fact=fact*i
print("Factorial=",fact)

15.
mydict={
"name":"prashant",
"professional":"developer",
"empid":1001
}
print(mydict)

16.
mydict={
    101:"prashant",
    102:"ashish",
    "103":"mohini",
    "104":"triveni",
    101:"ashish"
}
print(mydict)

17.
mydict={
    101:"prashant",
    102:"ashish",
    "103":"mohini",
    "104":"triveni",
    101:"ashish"
}
print(mydict)
#we will replace old value by new value 
mydict[102]="peter"
print(mydict)

18.
mydict={
    101:"prashant",
    102:"ashish",
    "103":"mohini",
    "104":"triveni",
    101:"ashish"
}
print(mydict)
#only print key x=0,1
for x in mydict:
    print(x)

19.
mydict={
    101:"prashant",
    102:"ashish",
    "103":"mohini",
    "104":"triveni",
    101:"ashish"
}
print(mydict)
#only print values
for x in mydict.values():
    print(x)

20.
mydict={
    101:"prashant",
    102:"ashish",
    "103":"mohini",
    "104":"triveni",
    101:"ashish"
}
print(mydict)
#printing key and values both
for x,y in mydict.items():
    print(x,y)

21.
mydict={
    101:"prashant",
    102:"ashish",
    "103":"mohini",
    "104":"triveni",
    101:"ashish"
}
print(mydict)
#if i have to add new key and value pair in my dictionary
mydict["mobile no"]=4646463738
print(mydict)

22.#pop() method remove pair by specific key name
mydict={
    101:"prashant",
    "professional":"developer",
    "empid":1001
}
mydict.pop(101)
print(mydict)

23.#Copy method
mydict={
    101:"prashant",
    "professional":"developer",
    "empid":1001
}
newdict=mydict.copy()
print(newdict)
      