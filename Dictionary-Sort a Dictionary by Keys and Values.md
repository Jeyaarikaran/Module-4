
---

## 🎯 Aim :
To write a Python script that reverses the contents of a file and saves the reversed content into another file.

## 🧠 Algorithm :

1.Create a file (create_file(input_file_path, file_content)):

   * Open the file at input_file_path in write mode ('w').

Write the provided file_content to the file.

   * Close the file after writing.

2.Reverse the file content (reverse_file_content(input_file_path, output_file_path)):

   * Open the input file in read mode ('r').

   * Read the content of the input file.

   * Reverse the content using Python string slicing ([::-1]).

   * Open the output file in write mode ('w').

   * Write the reversed content to the output file.

   * Close both the input and output files.

3.Read the content of the output file (read_file(output_file_path)):

   * Open the output file in read mode ('r').

   * Read the content of the output file.

   * Return the content of the file.

   * Close the output file.

4.Display the reversed content:

   * After reversing the content and saving it to the output file, print the content of the output file.

## 🧪Program :
```.py
def create_file(input_file_path,file_content):
    with open(input_file_path, 'w') as file:
        file.write(file_content)
def reverse_file_content(a,b):
    with open (a,'r') as f1,open (b,'w')as f2:
        data=f1.read()
        reversed_data=data[::-1]
        f2.write(reversed_data)
def read_file(file_path):
    with open(file_path, 'r') as f:
        return f.read()
```

## Output :
![image](https://github.com/user-attachments/assets/aae82cc0-f7fb-4086-9530-364bfc3eaec3)

## Result :
The program successfully takes input to create a file, reverses its content, saves it to a new file, and displays the reversed content from the output file.



