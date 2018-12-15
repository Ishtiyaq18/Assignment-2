# Assignment-2


#1. Write a program which accepts a sequence of comma-separated numbers from console and generate a list.

Output=[]
print('Type the desired number')
Numbers=input()
Output.append(Numbers)
print(Output)


#2. Create the below pattern using nested for loop in Python.
# *
# * *
# * * *
# * * * *
# * * * * *
# * * * *
# * * *
# * *
# *

n=5
for x in range(n):
    for j in range(x):
        print ('* ',end="")
    print('')
for x in range(n,0,-1):
    for j in range(x):
        print ('* ',end="")
    print('')


#3. Write a Python program to reverse a word after accepting the input from the user.
# Sample Output:
# Input word: AcadGild
# Output: dilGdacA

word=str(input())
print('Please type a word -',word)
print(word[::-1])


# 4. Write a Python Program to print the given string in the format specified in the sample output.
# WE, THE PEOPLE OF INDIA, having solemnly resolved to constitute India into a SOVEREIGN,
# SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC and to secure to all its citizens
# Sample Output:
# WE, THE PEOPLE OF INDIA,
# having solemnly resolved to constitute India into a SOVEREIGN, !
# SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC
# and to secure to all its citizens


string1=str('WE, THE PEOPLE OF INDIA,')
string2=str('having solemnly resolved to constitute India into a SOVEREIGN')
string3='SOCIALIST, SECULAR, DEMOCRATIC REPUBLIC'
string4='and to secure to all its citizens'
print(string1,"\n"," "*4,string2,"!","\n\t"," "*3,string3,"\n\t"," "*4,string4)
