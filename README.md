# Python-Reverse-Number
# Apporach-1
# Python program to reverse a number 
# Apporach-1
n = 4562
rev = 0
while(n > 0): 
	a = n % 10
	rev = rev * 10 + a 
	n = n // 10
print(rev) 

# Apporach-2

num = 1234
reversed_num = 0
while num != 0:
    digit = num % 10
    reversed_num = reversed_num * 10 + digit
    num //= 10
print("Reversed Number: " + str(reversed_num))

# Apporach-3

# Ask for enter the number from the use  
number = int(input("Enter the integer number: "))    
# Initiate value to null  
revs_number = 0    
# reverse the integer number using the while loop    
while (number > 0):  
    # Logic  
    remainder = number % 10  
    revs_number = (revs_number * 10) + remainder  
    number = number // 10    
# Display the result  
print("The reverse number is : {}".format(revs_number))  

# Apporach-4

# Reverse mathematically without converting into string
def reverse(num):
   rev=0
   while(num>0):
      digit=num%10
      rev=(rev*10)+digit
      num=num//10
   return rev
num=12345
print(reverse(num))
 
