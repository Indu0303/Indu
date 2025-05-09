# Indu
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
a=a+b
b=a-b
a=a-b
print("after swaping:")
print("a:",a)
print("b:",b)

num1=int(input())
num2=int(input())
total=num1+num2
print(total)

#string sample operations
s=str(input("enter a string:"))
print(s)
print(len(s))
print(s.upper())
print(s[1:3])
print(s[::-1])

#float data type sample
n1=float(input("enter a float value"))
n2=float(input("enter a float value"))
print("division:",n1/n2)


str1=str(input("enter a name"))
str2=str(input("enter a name"))
fullname=str1+str2
print(fullname)

str1=str(input("enter a name"))
str2=str(input("enter a name"))
fullname=str1+str2
print(fullname)

num1=input()
num2=input()
total=num1+num2
print(total)

num1=int(input())
num2=int(input())
total=num1+num2
print(total)


#list operatons
fruits=['apple','kiwi','orange']
print(fruits)
print('apple' in fruits)
print("insert")
fruits.append('banana')
print(fruits)
print("delete:")
fruits.remove('apple')
print(fruits)

#list with in a list
nest=[[1,2,],[3,4,],[5,6]]
print(nest)
print(nest[0])
print(nest[1][0])

#list with in a list
nest=[[1,2,],[3,4,],[5,6]]
print(nest)
print(nest[0])
print(nest[1][0])
print("modify:")
nest[2][1]=99
print(nest)
nest[2]=100
print(nest)

#list with in a tuple
student=("indu",[22,45,90],['math','science','english'])
print(student[0])
print(student[2][1])

#tuple sample
info=("indu",19,'Engineer')
print(info[0])

#tuple sample
info=("indu",19,'Engineer')
print(info[0])
print(info[-2])
print(len(info))
print(info*2)
print(info+(3,4))

#tuple sample
info=("indu",19,'Engineer')
print(info[0])
print(info[-2])
print(len(info))
print(info*2)
print(info+('12345',4))

#tuple within tuple
#nested tuple
nest=((1,2),(3,4),(5,6))
print(nest[0])
print(nest[1][0])

#dictionary operations
person={'name':'indu','age':20,'city':'vijawada'}
print(person)
print("accessing and modify the person age:")
person["age"]=17
print(person)

#dictionary operations
person={'name':'indu','age':20,'city':'vijawada'}
print(person)
print("accessing and modify the person age:")
person["age"]=17
print(person)
print("adding and removing items")
person['email']='induvadthiya@gmail.com'
print(person)
del person['city']
print(person)
print("all keys & values")
print(person,keys())
print(person,values())

#dictionary operations
person={'name':'indu','age':20,'city':'vijawada'}
print(person)
print("accessing and modify the person age:")
person["age"]=17
print(person)
print("adding and removing items")
person['email']='induvadthiya@gmail.com'
print(person)
del person['city']
print(person)
print("all keys & values")
print(person,allkeys())
print(person,values())

#dictionary operations
person={'name':'indu','age':20,'city':'vijawada'}
print(person)
print("accessing and modify the person age:")
person["age"]=17
print(person)
print("adding and removing items")
person['email']='induvadthiya@gmail.com'
print(person)
del person['city']
print(person)
print("all keys & values")
print(person.keys())
print(person.values())

ary operations
person={'name':'indu','age':20,'city':'vijawada'}
print(person)
print("accessing and modify the person age:")
person["age"]=17
print(person)
print("adding and removing items")
person['email']='induvadthiya@gmail.com'
print(person)
del person['city']
print(person)
print("all keys & values")
print(person,keys())
print(person,values())
print(person.get("age"))

#dictionary operations
person={'name':'indu','age':20,'city':'vijawada'}
print(person)
print("accessing and modify the person age:")
person["age"]=17
print(person)
print("adding and removing items")
person['email']='induvadthiya@gmail.com'
print(person)
del person['city']
print(person)
print("all keys & values")
print(person.keys())
print(person.values())
print(person.get("age"))

#nested dict
info={
    'vijay':{"salary":1200000,"perks":30000},
    'mark':{"slary":1800000,"perks":50000},
}
print(info['mark']['perks'])

#dictwith tuple keys
location={
    (40.7128, -73.070):'new york',
    (34.0522, -119.2347):'melbourn'}
print(location[(40.7128, -73.070])]



    #dictwith tuple keys
location={
    (40.7128, -73.070):'new york',
    (34.0522, -119.2347):'melbourn'}
print(location[(40.7128, -73.070)])


    #set operations
my_set={1,2,3,4,5,6}
print(my_set)
print("add and remove values")
my_set.add(7)
print(my_set)
my_set.remove(2)
print(my_set)
my_set.discard(5)
print(my_set)
print("membership check")
print(1 in my_set)
print(10 in my_set)

#program for basic operations by taking user input of an equation
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
c=int(input("enter the value of c:"))
x=int(input("enter the value of x:"))
result=a*(x**2)+ b*x +c
print("the result of the equation is ", result)

#swaping with temparary variable
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
print("before swap",a,b)
temp=a
a=b
b=temp
print("after swap", a,b)

#swaping using arithmetic operations
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
print("before swaping a= ", a,"b=v",b)
a= a+b
b= a-b
a= a-b
print("after swaping a=", a,"b= ",b)

#swaping using arithmetic operations
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
print("before swaping a= ", a,"b=",b)
a= a+b
b= a-b
a= a-b
print("after swaping a=", a,"b= ",b)


#date time and calender epoch time
from datetime import datetime
now=datetime.now()
print("current time:", now)
print("date:", now.date())
print("time: ", now.time())

from math import log,log10,exp,e
print("natural log:", log(e))
print("log base 10 of 100:", log10(100))
print("e to the power 2:",exp(2))

#power and squareroot
from math import sqrt , pow
n=16
print(sqrt(n))
print(pow(2,3))

pi=3.14159
r=float(input("enter the radius:"))
a=pi*(r**2)
c=2*pi*r
print("area: ",a)
print("circumference",c)

#swaping using arithmetic operations
a=int(input("enter the value of a:"))
b=int(input("enter the value of b:"))
print("before swaping a= ", a,"b=",b)
a= a+b
b= a-b
a= a-b
print("after swaping a=", a,"b= ",b)



#print first and last date of month
import calendar
from datetime import date
year=2025
month=5
fday=date(year,month, 1)
lday=date(year, month, calendar.monthrange(year, month)[1])
print("friday:",fday.strftime("%A, %Y-%M-%D"))
print("lastday:",lday.strftime("%A, %Y-%m-%d"))

import calendar
print(calendar.month(2005,3))

#day abbrevation
from datetime import date
today=date.today()
name=today.strftime("%A")
print("Today :", name)

#dates difference
from datetime import date
d1=date(2025, 5, 9)
d2=date(2025, 1, 1)
diff=(d1-d2)
print("difference in dates :",diff.days)

import calendar
year=2025
print(calendar.calendar(year))

#date time and calender epoch time
from datetime import datetime
now=datetime.now()
print("current time:", now)
print("date:", now.date())
print("time: ", now.time())

from math import floor , ceil
num=7.9
print("floor:",floor(num))
print("ceil:",ceil(num))

#power and squareroot
from math import sqrt , pow
n=16
print(sqrt(n))
print(pow(2,3))


