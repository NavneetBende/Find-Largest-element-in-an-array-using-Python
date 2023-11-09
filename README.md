# Find-Largest-element-in-an-array-using-Python

Largest Element in an array using python
Here, in this page we will discuss the program to find the largest element in an array using python we are given with an array elements and we need to print the largest among the given elements. We discuss different methods to find the largest element using python programing language.

Python Program to find largest element in an array
In this page we will discuss the following ways to find the maximum element among the given elements of the array.

Method 1 : Using Iteration
Method 2 : Using max() function
Method 3 : Using sort() function.
Method 1 :
Declare a variable say max_element and initialize it with a[0].
Run a loop for range a.len().
Check if(a[i]>max_element) then set max_element to a[i]
After complete iteration print(max_element)
Method 1 : Python code
Run
a = [10, 89, 9, 56, 4, 80, 8]
max_element = a[0]

for i in range(len(a)):
  if a[i] > max_element:
     max_element = a[i]

print (max_element)
Output :
89
Related Pages
Given a set of positive integers, find all its subsets
 
Given a string s, remove all its adjacent duplicate characters recursively
 
Find Smallest Element in an Array

Find the Smallest and largest element in an array

Find Second Smallest Element in an Array

Method 2 :
Sort the array using sort() function.
Print the last element of the array, i.e at index -1 (a[-1])
Largest element in an array in python
Method 2 : Python code
Run
a = [10, 89, 9, 56, 4, 80, 8]
a.sort()

print (a[-1])
Output :
89
Method 3 :
Using max() inbuilt function.

Declare an array.
Print the max(arr)
Method 3  : Python Code
Run
arr = [10, 89, 9, 56, 4, 80, 8]
print (max(arr))
Output :
89
