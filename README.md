# python-core-
----># Write a program to find sum of all the numbers in given range if starting index is greater than ending index print INVALID RANGE #
a=int(input())
b=int(input())
if(a>b):
    print("INVALID RANGE")
else:
    c=sum(range(a,b+1))
    print(c)
    -----or-----
'''__after else__
sum=0
for i in range(a,b+1);
  if(i%2==0):---> if we want to print even numbers
  sum=sum+i
  c=c+1
avg=sum/c
print("%.2f"%avg)'''
-->10-20=165

------->write a program to convert kg values into gram values?
a=float(input())
b=int(a*1000)
print(b,"Grams")
-->5.6=5600 Grams

------->Write a program to print all numbers which are divisible by 11 in given range if no such numbers print NO NUMBERS if starting range is greater than ending range then print INVALID RANGE
a=int(input())
b=int(input())
if a>b:
    print("INVALID RANGE")
else:
    c=0
    for i in range(a,b+1):
        if i%11==0:
            print(i,end=" ")
            c=c+1
    if c==0:
        print("NO NUMBERS")
-->30-100=33 44 55 66 77 88 99

------>write a program to perform all these tasks
a.     Store a number in a variable
b.    If value is not in range (100-1000) prints WRONG NUMBER else follows the steps
c.     Check even or odd
d.    If even divide the number by 3 and print the remainder
e.     If odd divide the number by 2 and print the remainder.
----->a=int(input())
if(100<=a<=1000):
    if(a%2==0):
        print(a%3)
    else:
        print(a%2)
else:
    print("WRONG NUMBER")
-->498=0
------>Write a Program to Print the Biggest Number out of the Given three Numbers?
a=int(input())
b=int(input())
c=int(input())
if(a>b):
    if(a>c):
        print(a,"is a Biggest Number from the Given Numbers")
    else:
        print(c,"is a Biggest Number from the Given Numbers")
else:
    if(b>c):
        print(b,"is a Biggest Number from the Given Numbers")
    else:
        print(c,"is a Biggest Number from the Given Numbers")
-->999-565=729
------->Write a program to print CVCORP for 'N' times
---- constrains:10<n<100-----
a=int(input())
if(10<a<100):
    for i in range(1,a+1):
       print("CVCORP")
else:
        print("Invalid Input")
-->2=CVCORP
     CVCORP
----->write a progrm to perform given tasks
Declare & initialize a number.
Check whether the number is in range 0-100 or not.
If not in range print INVALID INPUT
Else – if the number is in range 91-100 then print SUPER SMART,
81-90 print SMART,
71-80 print SMART ENOUGH,
61-70 print JUST SMART,
36-60 print NO SMART,
0-35 print DUMB.
-->a=int(input())
if(0<a>100):
    print("INVALID INPUT")
elif(91<=a<=100):
    print("SUPER SMART")
elif(81<=a<=90):
    print("SMART")
elif(71<=a<=80):
    print("SMART ENOUGH")
elif(61<=a<=70):
    print("JUST SMART")
elif(36<=a<=60):
    print("NO SMART")
else:
    print("DUMB")
Input :       62

Output :   JUST SMART

------>Write a program to convert temperature from degree celcisu (C) to Farenheit(F)
c=int(input())
f=(c*9/5)+32
print(f,end='F')
-->Input     :   96

Output  :   204.8F

------> Write a program to print all even numbers in range .if starting range is greater than ending range print "INVALID RANGE"
a=int(input())
b=int(input())
if(a>b):
    print("INVALID RANGE")
else:
    for i in range(a,b+1):
        if(i%2==0):
            print(i,end=" ")
Input :      1 10

output :   2 4 6 8 10            

------->Write a program to perform Addition, Subtraction, Multiplication and Division of 2 Numbers based on the user inputs by using Switch condition.(+ , - , * , /, %).
a=int(input())
b=int(input())
c=input()
match(c):
    case '+':
        print(a+b)
    case '-':
        print(a-b)
    case '*':
        print(a*b)
    case '//':
        print(a//b)
    case '%':
        print(a%b)
-->Input  :     30

                 10

                 +

Output :   40 
