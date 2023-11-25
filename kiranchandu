# python-practice using for multiplication table
number=4
counter=1
while counter<=10:
   result=number*counter
   print(f"{number}*{counter}={result}")
   counter+=1


   # reverse loop 
   for i in range(10,0,-1):
      print(i)


  counter=10
  while counter>=1:
     print(counter)
     counter-=1



# for factorial 

def factorial(n):
  result=1
  for i in range(1,n+1):
     result*=i
  return result

#reversing a 8 digit integer

number=23456798
num_str=str(23456798)
reversed_number = ""
for digit in number_str:
    reversed_number = digit + reversed_number
reversed_number = int(reversed_number)

print(f"Original Number: {number}")
print(f"Reversed Number (using for loop): {reversed_number}")


#array 

my_array=[1,2,3,4,5,6,7,8,9,10,11,12,13,1,4,15]
print(7)
print(10)
print(3)

inserting elements

my_array=[]
for i in range(0,14):
    my_array.append(i)
print(my_array)

read out elements
my_array=[]
for i in range(1, 16):
    user_input = int(input(f"Enter item {i}: "))
    my_array.append(user_input)
print(my_array)


fidning even or odd

numbers = [123, 4567, 89, 10000, 98765, 4321, 876543]


even_digit_numbers = []
odd_digit_numbers = []


for num in numbers:
    num_digits = len(str(num)
    if num_digits % 2 == 0:
        even_digit_numbers.append(num)
    else:
        odd_digit_numbers.append(num)


print("Numbers with even number of digits:", even_digit_numbers)
print("Numbers with odd number of digits:", odd_digit_numbers)



 squares

 my_array=[2,4,5,6,7]
squares_array=[x**2 for x in my_array]
print(squares_array)

insert any where

my_array=[2,4,5,6,7]
my_array.append(9)
print(my_array)


remove duplicates

my_array=[2,4,4,4,4,4,5,6,7,7,8,8,8,7]
new_array=list(set(my_array))
print(new_array)


def merge_sorted_arrays(arr1, arr2):
    merged_array = []
    i = j = 0
    while i < len(arr1) and j < len(arr2):
        if arr1[i] < arr2[j]:
            merged_array.append(arr1[i])
            i += 1
        else:
            merged_array.append(arr2[j])
            j += 1
    while i < len(arr1):
        merged_array.append(arr1[i])
        i += 1
    while j < len(arr2):
        merged_array.append(arr2[j])
        j += 1

   return merged_array

