# 4b.py
Given a list of numbers,write a Python program to count Even and Odd numbers in a List. Input:list2 = [12,14,95,3]  
list1 = [12, 14, 95, 3] - input

only_odd = [num for num in list1 if num % 2 == 1] - for seperation of odd numbers

odd_count = len(only_odd) for counting of odd numbers

print("Even numbers in the list: ", len(list1) - odd_count) - for counting of even numbers

print("Odd numbers in the list: ", odd_count)- for displaying number of odd and even numbers
