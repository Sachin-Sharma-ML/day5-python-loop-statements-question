# day5-python-loop-statements-question
 Python while and for Statements practice Question code
# for and while loop question
# 1 Write a program to print numbers from 1 to 10 using for loop
for i in range(1,11):
    print(i)

# 2 Write a program to print even numbers from 1 to 50 using a for loop

for i in range(1,51):
    if i % 2 == 0:
        print(i,"is even number")


# 3 Write a program to print the multiplication table of a given number using a for loop

num=int(input("Enter a number :"))
for i in range(1,11):
    print(num,"X",i,"=",num*i)

# 4 Write a program to calculate the sum of n natural numbers using a for loop

num=int(input("Enter a natural number :"))
sum=0
for i in range(1,num+1):
    sum = sum + i
print("Sum of first",num,"natural numbers is ",sum)

# 5 Write a program to count a vowels in a given string a for loop
text = (input("Enter a string:"))
count=0
for ch in text:
    if ch.lower() in 'aeiou':
        count+=1
print("The numbers of vowels:",count)

# while loop

# 1 write a program to print numbers from 10 to 1 using a while loop
num=10
while(num>=1):
    print(num)
    num-=1
# write a program to find the sum of digit of a number using a while loop
num=int(input("Enter a number :"))
sum=0
while(num>0):
    digit=num%10
    sum=sum+digit
    num=num//10
    print("sum of digit:",sum)

# 3 Write a program to print the multiplication table of a given number using a while loop
num=int(input("Enter a number :"))
i=1
while(i<=10):
    print(num,'X',i,'=',num*i)
    i+=1

# 4 reverse number using a while loop
num=int(input("Enter a number:"))
rev=0
while num>0:
    digit=num%10
    rev=rev*10+digit
    num=num//10
    print("Reverse number :",rev)

# 5 palindrome or not using while loop
num=int(input("Enter a number:"))
temp=num
rev=0
while temp>0:
    digit=temp%10
    rev=rev*10+digit
    temp=temp//10
if num==rev:
    print("Palindrome number")
else:
    print("Not aPalindrome number")
   
