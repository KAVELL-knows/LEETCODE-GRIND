# LEETCODE-GRIND
Doing LeetCode questions until I complete every single question. 

21/08/2026
Excel Sheet Column Number

Class Solution: Ignore this. This is where we do the solution to the problem, and it does not do anything 

 def titleToNumber(self, columnTitle: str) -> int:
 This is also not that Important: 
 We are defining a function, and for that function our input is some string called ColumnTitle, and they want us to give a return in the form of an integer int 

 def add(a, b):
    result = a + b
    return result

  so in future x = add(5, 3) would just give 8 

Print is displayed on a screen

Return 
Give this value back to the code that called my function.

When we define a function, we use the return statement to end a function right away and send a value back to where you called it.


03/09/2026
CODE FOR FIBONACCI NUMBERS 

p = int(input())
count = 0 
n = 1
for i in range(p):
    count, n = n, n + count 
print(n)


04/09/2026
1. You can write 

n = n // 5 as n //= 5


2. The idea you would toward prime factorization of a number:
n = int(input())
("NOT UGLY")
 while n % 2 == 0:
   n  = n // 2
while n % 3 == 0:
   n  = n // 3
while n % 5 == 0:
        n  = n // 5
print(n)
you get the prime number left, or 1. 


21/09/2026
.remove() removes an integer from a list


26/09/2026
Instead of typing
if j == "q" or j == "w" or j == "e" or j == "r" or j == "t" or j == "y" or j == "u" or j == "i" or j == "o" or j == "p":

we can say 

if j in "qwertyuiop":
# Python automatically checks every letter for you!


02/10/2026
Here is an idea for getting the max product of 3 integers in a list from negative infinity to positive infinity 

So either we take the 3 largest integers and multiply them
or we take the 2 smallest negative integers and multiply that by the largest positive 

We then compare and choose the maximum 


04/10/2026

Here is a nice idea in a for loops

Let's say we were doing an if statement, and we wanted the if statement to only occur if the end of the for loop was met

then we could for i in range(len(x)):
   if i == len(x) -1

Here is an example where I used this idea: 

for i in range(len(nums)):
    if nums[i] * 2 > largest and nums[i] != largest:
        print("-1")
        break
    elif i == len(nums) - 1:
        for i in range(len(nums)):
            if nums[i] == largest:
                print(i)
                break

09/10/2026

.index() method searches for a specified element within a sequence (like a list, string, or tuple) and returns its first zero-based position

fruits = ['apple', 'banana', 'cherry', 'banana']

print(fruits.index('banana')) 
Output: 1

print(fruits.index('orange')) 
Output: ValueError: 'orange' is not in list
