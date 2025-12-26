## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
      def merge(dict1,dict2):
          merged_dict = {**dict1 , **dict2}
          print(merged_dict)
      dict1 = eval(input("Dictionary-1 : "))
      dict2 = eval(input("Dictionary-2 : "))
      merge(dict1,dict2)



## Output
<img width="1917" height="512" alt="503496624-5e380c1d-4366-41f5-8b13-24713e1f4da5" src="https://github.com/user-attachments/assets/cfd3d196-993e-413c-bd92-3b3ece381894" />


## Result
Thus, The Python program that merges two dictionaries and combines their key-value pairs was executed sucessfully.
