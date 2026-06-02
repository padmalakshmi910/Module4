## Classes and Objects in Python: Calculate the Area of a Circle
## Aim
To write a Python program that calculates the area of a circle based on the radius provided by the user. This program uses a class named cse and a method mech to perform the calculation.

## Algorithm
```
1.Get user input: Take the radius of the circle as input from the user.
2.Define the class: Create a class named cse.
3.Define the method: Inside the class, define the method mech to calculate the area of the circle using the formula:
4.Area = pi *r^2
5.Execute the program: Create an object of the class and call the method with the radius value.
```
## Program
```
import math
class cse:
    def mech(self, r):
        c = math.pi * r**2
        print(f"Area of circle: {c:.2f}")

r = int(input("Enter radius: "))
ci = cse() 
ci.mech(r)
```
## Output
<img width="1183" height="365" alt="Screenshot 2026-06-01 181412" src="https://github.com/user-attachments/assets/db44b3a4-46ae-4526-bf65-5b64efc45745" />

## Result
Thus, the program has been executed successfully.

Dictionary Operations in Python: Merging Two Dictionaries
🎯 Aim
To write a Python program that merges two dictionaries and combines their key-value pairs.

## Algorithm
```
1.Define two dictionaries dict1 and dict2 with some key-value pairs.
2.Define a function merge() that merges the two dictionaries using the ** unpacking operator.
3.The merged result will combine keys from both dictionaries. If a key exists in both, the value from dict2 will overwrite that from dict1.
4.Call the merge() function and print the merged dictionary.
```
## Program
```
dict1 = {'a': 1, 'b': 2}
dict2 = {'c': 3, 'd': 4}
dict1.update(dict2)
print(dict1)
```
## Output
<img width="1364" height="304" alt="Screenshot 2026-06-01 181607" src="https://github.com/user-attachments/assets/a686969b-e551-4b75-9471-1bad844f2b62" />
## Result
Thus, the program has been executed successfully.

## Dictionary-Python Program to Sort a Dictionary by Keys and Values
This Python program demonstrates how to sort a dictionary:

Alphabetically by keys
Alphabetically by values
## Aim
To write a Python program that sorts a dictionary's:

Keys in alphabetical order
Values in alphabetical order
## Algorithm
```
1.Start the program.
2.Define a dictionary with key-value pairs.
3.Sort by Keys:
Use sorted(dictionary.items())
Convert the result to a dictionary using dict()
4.Sort by Values:
Use sorted(dictionary.items(), key=lambda item: item[1])
Convert the result to a dictionary using dict()
Display the original and sorted dictionaries.
5.End the program.
```
## Program
```
d={2:56,1:2,5:12,4:24,6:18,3:323}
l=[]
for i in d:
    l.append(i)
l.sort()
print("Keys and Values sorted in alphabetical order by the key")
for i in l:
    print(tuple([i,d[i]]),end=" ")
```
## Output
<img width="1426" height="367" alt="Screenshot 2026-06-01 182222" src="https://github.com/user-attachments/assets/e0d62d1d-124b-4611-af44-d8c894850794" />

## Result
Thus, the program has been executed successfully.

## Exception Handling in Python: Avoiding Index Errors
## Aim
To write a Python program that handles an IndexError when trying to access an element beyond the available range of a list.

## Algorithm
```
1.Define a list list1 with some integer elements.
2.Use a try-except block:
3.In the try block, attempt to access an index that is out of range (e.g., list1[5]).
4.In the except block, catch the error and print a custom message "You're out of list range".
5.Print the result based on whether the index access succeeds or fails.
```
## Program
lis=[5, 10, 20]
try:
    print(lis[5])
except:
    print("You're out of list range")
## Output
<img width="1360" height="309" alt="Screenshot 2026-06-01 182621" src="https://github.com/user-attachments/assets/4f5b5980-bae9-4d59-abf0-98da527f5c6d" />

## Result
Thus, the program has been executed successfully.

## File Handling in Python: Count Lines Not Starting with 'T'
## Aim
To write a Python program that counts the number of lines in a text file story.txt that do not start with the alphabet 'T'.

## Algorithm
```
1.Open the file story.txt in read mode.
2.Initialize a counter count to zero.
3.Iterate through each line of the file:
4.Check if the first character of the line is not 'T'.
5.If the line does not start with 'T', increment the count by 1.
6.After processing all lines, print the count value, which represents the number of lines that do not start with 'T'.
```
## Program
```
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final
myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))
```
## Output
<img width="1285" height="317" alt="Screenshot 2026-06-01 183828" src="https://github.com/user-attachments/assets/9c6fbc55-7bb3-4654-9f96-5205236c9899" />
## Result

Thus, the program has been executed successfully.
