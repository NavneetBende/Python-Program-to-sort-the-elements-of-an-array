# Python-Program-to-sort-the-elements-of-an-array


Sort the Array in Python
Here, in this page we will discuss the program to sort elements of the given array in Python programming language. We will discuss the program to sort the given input array using inbuilt sort function.

Here, in this page we will sort the given input array but not only in ascending order, but also in descending order.

Example :
Input : arr[5] = [10, 40, 20, 30]
Output : In ascending order = 10 20 30 40
               In descending order = 40 30 20 10
Method 1 (Sort in ascending order):
In this method we will sort the given input array using inbuilt sort function.

Declare an array.
Call sort() function i.e, arr.sort()
This will sort the given input array in ascending order. We will also discuss to sort the given input array in descending order as well.

sort() function
The sort() method is a built-in Python method that, by default, sorts the list in ascending order.
However, you can modify the order from ascending to descending by specifying the sorting criteria.
Sort the array in python
Code to Sort the Array in Python
Run
# List of Integers
numbers = [10, 30, 40, 20]

# Sorting list of Integers
numbers.sort()

print(numbers)
Output
[10, 20, 30, 40]
Related Pages
Reverse an Array

Sort first half in ascending order and second half in descending

Finding the frequency of elements in an array

Sorting elements of an array by frequency

Finding the Longest Palindrome in an Array

Method 2 (Sort in descending order):
In this method we will sort the given input array using inbuilt sort function.

Declare an array.
Call sort() function i.e, arr.sort(reverse=True)
This will sort the given input array in descending order.

reverse parameter
On passing parameter reverse with value True, i.e, reverse-True : Then the array will get sorted in descending order
Code to Sort the Array in Python
Run
# List of Integers
numbers = [10, 30, 40, 20]

# Sorting list of Integers
numbers.sort(reverse=True)

print(numbers)
Output
[40, 30, 20, 10]
