# Dictionary : To find sum of all items in a Dictionary 

## 🎯 Aim :
To write a Python program that calculates the sum of all values in a dictionary.

## 🧠 Algorithm :
1.Define a dictionary with numeric values.

2.Use the sum() function with dictionary.values() to get the sum of all values.

3.Print the result.

## 🧾 Program :
```.py
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final
#driver functions

myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))
```
## Output : 
![image](https://github.com/user-attachments/assets/c18f0d99-6b3f-4c39-b4a4-824174d50666)

## Result :
The program successfully computes and displays the sum of all values in the dictionary.
