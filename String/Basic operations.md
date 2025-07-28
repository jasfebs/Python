**Create string str() builtin function**

Pass a value (of any datatype) to str() builtin function, and the function returns the string value.

In the following statement, we create a string from a number, using str() function, and assign it to variable x.

**x = str(1024)**

** Create an empty string using str()**
In the following program, we create empty string using str() builtin function. Pass no value as argument to str() function. The function returns an empty string.

Python Program
**x = str()
print('x :', x)**

**Create string from list using string join() method in Python**
Using string join() method, you can join the elements of the given list using a given separator string. 

The separator string can be an empty string, comma, or any valid string.

Creating a string by joining items in list with empty string as separator

In the following program, we take a list of three items in my_list,

and create a string value from this list, by joining the items in the list, with an empty string separator.

Python Program
# Given list
my_list = ["apple", "banana", "cherry"]

# Convert list to string
result = "".join(my_list)

# Print resulting string
print(result)

**Output
applebananacherry**

**Creating a string by joining items in list with comma as separator**

In the following program, we take a list of three items in my_list, and create a string value from this list, by joining the items in the list, with an empty string separator.

Python Program

# Given list

my_list = ["apple", "banana", "cherry"]

# Convert list to string

result = ",".join(my_list)

# Print resulting string

print(result)

Output
**apple,banana,cherry**

---

<img width="1472" height="476" alt="image" src="https://github.com/user-attachments/assets/38e1915f-49df-4eb3-8658-fff1d797f695" />


---

**Create string from two variables using formatted string in Python**

# Given variables
name = "Apple"
age = 12

# Formatted string
result = f"Name is {name}, and age is {age}."

# Print resulting string
print(result)

