## Exception- Key error using exception handling & to find whether  key is exist or not. 

## 🎯 Aim
To write a Python program that checks whether a given key exists in a dictionary using exception handling. If the key doesn't exist, the program should handle the KeyError and display a message: "The key does not exist!".
## 🧠 Algorithm :
1.Define a dictionary my_dict with keys 1, 2, and 3 and corresponding values "Hello", "World", and "Python".

2.Prompt the user to input a key to check.

3.Use a try block to attempt to access the dictionary using the provided key.

4.If the key exists, print the corresponding value.

5.If the key does not exist, a KeyError will occur, which is caught by the except block.

6.The except block will print the message: "The key does not exist!" if a KeyError occurs.

7.End the program.

## 🧾 Program :
```.py
dict1={1:'Hello',2:'World', 3:'Python'}
try:
    a=dict1[1]
    print(a)
    b=dict1[2]
    print(b)
    c=dict1[4]
    print(c)
except:
    print("The key does not exist!")
```



## Output :
![image](https://github.com/user-attachments/assets/914277d8-c463-4476-96ce-dc5d5500a9a4)


## Result :
The program correctly handles a KeyError by using exception handling. If the key exists in the dictionary, the program displays its value; if the key does not exist, it displays the message: "The key does not exist!".
