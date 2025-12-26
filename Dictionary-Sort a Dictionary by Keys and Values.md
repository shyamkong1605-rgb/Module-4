# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
      dict = {'b':1,'e':27,'c':7,'a':3,'d':15}
      
      # To sort dictionary by keys
      sort1 = sorted(dict.items())
      print("The Sorted Dictionary by keys.....")
      dict1={}
      for key,value in sort1:
          dict1[key] = value
      print(dict1)
      
      print()
      
      # To sort dictionary by values
      sort2 = sorted(dict.items(),key = lambda item : item[1])
      print("The Sorted Dictionary by values.....")
      dict2 = {}
      for key,value in sort2:
          dict2[key] = value
      print(dict2)

## Sample Output
<img width="1918" height="842" alt="503505928-30016f47-8c1b-48ed-a00c-3e580116bb4f" src="https://github.com/user-attachments/assets/6584c48c-b95d-47ad-a14b-3f43ef061eee" />


## Result
Thus, The To write a Python program that sorts a dictionary according to its Keys in alphabetical order and to its Values in alphabetical order was executed successfully.

