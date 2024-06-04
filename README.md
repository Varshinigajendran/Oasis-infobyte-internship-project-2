import random

uppercase="ABCDEFGHIJKLMNOPQRSTUVWXYZ"
lowercase="abcdefghijklmnopqrstwxyz"
numbers="0123456789"
symbols="!@#$%^&*()."

str=uppercase+lowercase+numbers+symbols
len=int(input("Enter The Length : "))
password="".join(random.sample(str,len))
print("Your Password Is : ",password)
