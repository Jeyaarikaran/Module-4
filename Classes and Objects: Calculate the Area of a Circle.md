# Dictionary-To Sorting the Keys and Values in Alphabetical Order using the Key in Dictionary.

## 🎯 Aim :
To write a Python program that sorts a dictionary’s keys and values in alphabetical order by the key and displays the sorted pairs.

## 🧠 Algorithm
1.Define a dictionary with key-value pairs.

2.Use the sorted() function on the dictionary’s .items() method to sort the items based on the keys.

3.Loop through the sorted items and print the key-value pairs.

4.End the program.

## 🧾 Program :
```.py
list1=[]
dict1={}
for i in range(10):
    a=int(input())
    list1.append(a)
for i in list1:
    if i==2 or i==3 or i==5 or i==7:
        dict1.update({i:"prime"})
    elif i%2!=0 and i%3!=0 and i%5!=0 and i%7!=0 and i!=1:
        dict1.update({i:"prime"})
    else:
        dict1.update({i:"not prime"})
print(dict1)
```
Add code here

## Output :
![image](https://github.com/user-attachments/assets/939a4b97-658a-45d7-8697-b8e3e0c912c8)


## Result :
The program successfully sorts the dictionary items in ascending order by their keys and prints the key-value pairs in sorted order.
