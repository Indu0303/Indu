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
