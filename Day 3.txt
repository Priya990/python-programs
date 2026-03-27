Day 3
1.Collecting Datatype
mylist=["prashant","Ashish","komal","ankush",77,"sandip",60.52,"prashant"]
print(mylist)
print(type(mylist))
print(mylist[0])
print(mylist[1])
print(mylist[2])
print(mylist[-1])
print(mylist[2:5])
print(mylist[:5])
print(mylist[1:])
print(mylist[1:8:2])
print(mylist[:])
print(mylist[::-1])

2.
mylist=["prashant","Ashish","komal","ankush",77,"sandip",60.52,"prashant"]
mylist[2]="Akshay"
print(mylist)

3.#in operator can be used to check the values is list in the or not(yes or no)
mylist=["prashant","Ashish","komal","ankush",77,"sandip",60.52,"prashant"]
print(mylist)
if "ankush" in mylist:
    print("yes ankush is available")
else:
    print("not available")

4.#Append Function
mylist=["prashant","Ashish","komal","ankush",77,"sandip",60.52,"prashant"]
print(mylist)
# Using Append function()
mylist.append('harsh')
mylist.append("laxman")
print(mylist)

4.#Insert mathod
mylist=["prashant","Ashish","komal","ankush",77,"sandip",60.52,"prashant"]
print(mylist)
#using insert mathod so every object will bw shifted to right side
mylist.insert(1,"sanket")
print(mylist)

5.#Remove method
mylist=["prashant","Ashish","komal","ankush",77,"sandip",60.52,"prashant"]
print(mylist)
#using remove method 
mylist.remove("sandip")
print(mylist)

6.#Copy method
mylist=["prashant","Ashish","komal","ankush",77,"sandip",60.52,"prashant"]
print(mylist)
newlist=mylist.copy()#cloning
print(mylist)
print(newlist)

7.#Multidimensional list method
mlist=[['prashant','jha'],['85.56'],[440022,"yyy"]]
print("example of multidimensional list:")
print(mlist)
#print(mylist[row][col])
print(mlist[0][0])#prashant
print(mlist[0][1])#jha
print(mlist[1][0])#85.56
print(mlist[2][0])#4440022
print(mlist[2][1])#yyy               

hint:
[     0          1
0=['prashant', 'jha'],
1=['85.56'],
2=[440022,     "yyy"]]

8.#Duplicate method
list1=["prashant","jha"]
print(list1*2)

9.#combining method
list1=["prashant","jha"]
list2=[50,25,50]
print(list1+list2)

10.#delete the index value
list2=[50,25,50,'prashant']
del list2[2]
print(list2)

11.#
v=[1,2,3,4,5]
for i in v:
    print(i)

12.#clear the empty list
list3=[50,25,50,'prashant']
list3.clear()
print(list3)#[]

13.#List constructor
name="prashant"#str
print(name)
myname=list(name)#typecasting=converting str into list
print(myname)#['p','r','s'....]
#we have used list constructor

14.#reverse list
mylist=[40,30,20,10]
mylist.reverse()
print(mylist)

15.#sorting example
mylist=[44,22,77,0,9,88]  # 0, 9, 22, 44, 77, 88
mylist.sort()  #sort(reverse=True)
print(mylist)

#default sorting order for number is ascending order
#default sorting order for string is alphabetical order
#we should know that list should contain homogenious
#data otherwise we will get typeerror
#python2 first short number then string follow

16.#Alicing method example
mylist=[44,22,77,0,9,88]
newlist=mylist #both list having same adderss
print(id(mylist))
print(id(newlist))

17.#Tuple method
mytuple=("prashant","Ashish","rahul","sandip","komal","ankush","rajesh",23,3.15,77,"sandip")
print(mytuple)
print(type(mytuple))

18.#The value once assign to the tuple we can't change it so it ia immutable
mytuple=("prashant","Ashish","rahul","sandip","komal","ankush","rajesh",23,3.15,77,"sandip")
mytuple[2]="sunil"
print(mytuple)
 
#membership operator:
#1.in
#2.not in

19.
print('z' in "Prashant")
print('z' not in "Prashant").

20.
print('z' in "Prashant")
print('z' not in "Prashant")
print('a' in "Prashant")
mylist=[3,5,2,8,9]
print(3 in mylist)

21.#identity operator method
a=10
b=10
print(id(a))
print(id(b))
print(a is b)#True
print(a is not b)#False

22.#set datatype=means we get random output
myset={1,2,"sanjay",5.66,"rahul","ayush","ramesh","ankit",'rishikesh'}
print(myset)
print(type(myset))

23.add value to set datatype
myset={1,2,"sanjay",5.66,"rahul","ayush","ramesh","ankit",'rishikesh'}
print(myset)
# print(type(myset))
myset.add(60)
print(myset)

24.discard
myset={1,2,"sanjay",5.66,"rahul","ayush","ramesh","ankit",'rishikesh'}
print(myset)
# print(type(myset))
myset.discard(3)
print(myset)

25.remove=we can get error
myset={1,2,"sanjay",5.66,"rahul","ayush","ramesh","ankit",'rishikesh'}
print(myset)
# print(type(myset))
myset.remove(3)
print(myset)

#when we use remove we sure that the value is present.
#we use discard when we are not sure the value is present

26.#Union set
myset={10,20,30,40}
yorset={"prashant","jha"}
newset=myset.union(yorset)
print(newset)

27.#intersection return common element
myset={10,20,30,40}
yorset={10,50,60,30}
print(myset.intersection(yorset)) 

28.#difference metod this will return the element
#present in first set but not in second set
myset={10,20,30,40}
yorset={10,50,60,30}
print(myset.difference(yorset))

#Logic Building questions
1>#WAP to accept 3 numbers like a,b,c and find max number
#Nested if else:

if condition-1:
    if condition-2:
        #statement
    else:
        #statement
else:
    if condition-3:
        #statement
    else:
        #statement
=>#WAP to accept 3 numbers like a,b,c and find max number
#Nested if else:
a=int(input("Enter the value of a:"))#5
b=int(input("Enter the value of b:"))#10
c=int(input("Enter the value of c:"))#20
if a>b:#5>30
    if a>c:
        print("A is greater")
        #statement
    else:
        print("C is greater")
        #statement
else:
    if b>c:#10>20
        print("B is greater")
        #statement
    else:
        print("C is greater")
        #statement

2>#WAP to accept 3 numbers like a,b,c and find min number
#Nested if else:
a=int(input("Enter the value of a:"))#5
b=int(input("Enter the value of b:"))#10
c=int(input("Enter the value of c:"))#20
if a<b:#5<10
    if a<c:#5<30
        print("A is lesser")
        #statement
    else:
        print("C is lesser")
        #statement
else:
    if b<c:#10<20
        print("B is lesserr")
        #statement
    else:
        print("C is lesserr")
        #statement
3.
mylist=[3,4,5,8,2]
for i in mylist: #i=5
    print(i)

4.#for(initialization; condition; inc/dec)
for i in range(5): #i=2
    print(i)

5.#for(initialization; condition; inc/dec)
for i in range(1,11,2): #i=2
    print(i) #1 3 4 7 9

6.#for(initialization; condition; inc/dec)
for i in range(1,11): #i=2
    print(i*2) #1 3 4 7 9

7.#for(initialization; condition; inc/dec)
for i in range(1,11): #i=2
    print(i*2,"   ",i*3,"   ",i*4,"   ",i*5) 
#output:
2     3       4       5     6    7     8     9    10
4      6      8      10    12    14    16    18    20
6      9      12     15    18    21    24    27    30
8      12     16     20    24    28    32    36    40
10     15     20     25    30    35    40    45    50
12     18     24     30    36    42    48    54    60
14     21     28     35    42    49    56    63    70
16     24     32     40    48    56    64    72    80
18     27     36     45    54    63    72    81    90
20     30     40     50    60    70    80    90    100

8.
username=input("Enter Username:")
password=input("Enter password:")
if username==password:
    print("login successful")
else:
    print("Invalid login")

9.
brand=input("Enter your coldrink name either in uppercase or in lowercase but not combine:")
if brand=="pepsi" or brand=="PEPSI":
    print("swag")
elif brand=="dew" or brand=="DEW":
    print("dar age jeet hai")
elif brand=='thumsup' or brand=='THUMSUP':
    print('taste the thunder')
else:
    print('go with your brand')

10.
n1=int(input("Enter the first number:"))#5
n2=int(input("Enter the second number:"))#2
n3=int(input("Enter the third number:"))#7
if n1>n2 and n1>n3:
    print("Biggest Number is:",n1)
elif n2>n3:
    print("Biggest Number is:",n2)
else:
    print("Biggest Number is:",n3)

11.
count=0
for i in range(9):
    if i%2==0:
        print(i)
    else:
        print(i)
        count+=1
print("count=",count)