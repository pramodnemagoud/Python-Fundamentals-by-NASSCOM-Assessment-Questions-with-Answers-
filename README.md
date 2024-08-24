# Assessment Questions with Answers on  Python Fundamentals Aligned to Competency Standards developed by IT-ITeS Sector Skills Council  NASSCOM in collaboration with Industry and approved by Government by solving this questions I got NASSCOM certification 

###Q1. Consider two lists in Python named `example1`: `["Blue", 35.6, 100, "Red", "Pink"]` and `example2`: `["Purple", 1, 7.3]`. A programmer wants to merge these two lists in such a way that elements of the `example2` list are added one by one at the end of the `example1` list, i.e., the below given output is obtained:
['Blue', 35.6, 100, 'Red', 'Pink', 'Purple', 1, 7.3]
Which of the following is the correct syntax of the code that will do the needful?

1. ```python
   example1 = ["Blue", 35.6, 100, "Red", "Pink"]
   example2 = ["Purple", 1, 7.3]
   example1.append(example2)
   print(example1)
   ```

2. ```python
   example1 = ["Blue", 35.6, 100, "Red", "Pink"]
   example2 = ["Purple", 1, 7.3]
   add(example1, example2)
   print(example1)
   ```

3. ```python
   example1 = ["Blue", 35.6, 100, "Red", "Pink"]
   example2 = ["Purple", 1, 7.3]
   merge(example1, example2)
   print(example1)
   ```

4. ```python
   example1 = ["Blue", 35.6, 100, "Red", "Pink"]
   example2 = ["Purple", 1, 7.3]
   example1.extend(example2)
   print(example1)
   ```

Answer: 4

------------------------------------------------------------------------------------------------------------------------
Q2. Which of the following is NOT a correct feature of Sets in Python?

1. Set values are mutable
2. Sets are unordered
3. Sets do not allow duplication
4. Set items are unchangeable

Answer:4

------------------------------------------------------------------------------------------------------------------------
 Q3. A programmer created two empty sets and printed them using the following code:
sample1 = set()
sample2 = set()
print(sample1, sample2)
Now he wants to extend this code in such a way that the following output is printed on compilation:
Output:
set() set()
{1}
{1, 2}
{1, 2, 3}
{1, 2, 3, 4}
{1, 2, 3, 4, 5}
{6}
{6, 7}
{8, 6, 7}
{8, 9, 6, 7}

Which of the following code snippets should he add at the end of the given code in order to get this output?

1. The given set code cannot be extended as the sets are non-extendable. The programmer must write separate code for this output.
2. ```python
   for range i: (0, 5):
       sample1.get(i)
       print(sample1)
   for range i: (6,10):
       sample2.get(i)
       print(sample2)
   ```

3. ```python
   for range i = (1, 6):
       sample1.include(i)
       print(sample1)
   for range i = (6,10):
       sample2.include(i)
       print(sample2)
   ```

4. ```python
   for i in range(1, 6):
       sample1.add(i)
       print(sample1)
   for i in range(6, 10):
       sample2.add(i)
       print(sample2)
   ```
Answer:4
------------------------------------------------------------------------------------------------------------------------

Q4. Analyse the below given Python code snippet.

Which of the following code snippets should be there in place of the question mark “??” so that the following output is printed on the compilation?

x = "New Sample"
??
   ??
    try:
        n = next(y)
        print(n)
    except StopIteration:
        break
```

**Output:**
```
N
e
w

S
a
m
p
l
e
```
1  y = iteration(x)
   while true:

2.    y = iter(x)
   while True:
   ```

3. ```python
   y = itern(x)
   while enabled:
   ```

4. ```python
   y = iterate(x)
   while Enabled:
   ```
Answer: 2

Q5. Sam wrote a Python programme that takes a numeric value as input from the user and then prints its factorial value. The program, however, contains errors and is not running and producing the desired result.
1) n = int(input("Enter a number:"))
2) fact = 1
3) if n < 0:
4)     print("Factorial is not calculated for negative value")
5) elseif n == 0:
6)     print("Factorial is 1")
7) else:
8)     when i in range (1,n):
9)         fact = fact * i
10)         print(fact)
Analyse the programme code and identify the line numbers that contain errors.
1. Line 3 and Line 5
2. Line 1 and Line 3
3. Line 5 and Line 8
4. Line 1, Line 5 and Line 9
Answer: 3

Q6. In Python, which of the following files must be present in a package and module?
1. A package must hold the `_init_.py` file while a module must hold `_exec_.py` file
2. A package must hold the `_exec_.py` file while a module must hold `_init_.py` file
3. A package must hold the `_init_.py` file while no such condition is applicable for modules
4. Both, the package and a module, must hold the `_exec_.py`
Answer: 3

Q7. A programmer has written the following Python code snippet.
a1 = {0: 'False', 1: 'False'}
print(all(a1))
a2 = {1: 'True', False: 0}
print(all(a2))
What will happen when this code is executed?

1. Code will compile successfully, and it will print the following output:<br />
   `False`<br />
   `False`
2. Code will compile successfully, and it will print the following output:<br />
   `True`<br />
   `True`
3. Code will throw an error at line 3
4. Code will compile successfully, and it will print the following output:<br />
   `False`<br />
   `True`
Answer: 4

Q8. While using regular expression in Python, which of the following options should a user choose if he wants to match any whitespace character, equivalent to `[tnrfv]` in a string pattern with the ASCII flag?
1. `\W`
2. `\w`
3. `\s`
4. `\S`
Answer:3

 Q9. Which of the following string declarations are valid in Python?
1. [i] `mystring1 = 'example'`
2. [ii] `mystring1 = "example"`
3. [iii] `mystring1 = '''example'''`
4. [iv] `mystring1 = ' "" '`

1. Only i and ii
2. i, ii, iii, and iv
3. Only ii and iv
4. Only i and iv

Answer: 2

Q10. A programmer is working with a long string in a Python program.
Which of the following commands should be added to the given code in order to get the following output?
Output:
['87654', '876543', '8765432', '8765432']

Code Snippet:
import re
values = "876 8765 87654 876543 8765432 87654321"
??

1. ```python
   res = re.findall("\d{5,7}", values)
   print(res)
   ```

2. ```python
   res = re.getAll("\d{5,7}", values)
   print(res)
   ```

3. ```python
   res = re.get("\d[5-7]", values)
   print(res)
   ```

4. ```python
   res = re.search("\d[5-7]", values)
   print(res)
   ```
Answer:** 1

Q11. A user is importing data from a file named `example1.csv` using Pandas. He is using the `mba` data set.

During the process, which of the following options can be used to get the size of the dataframe?

A. `mba.structure`

B. `mba.frame`

C. `mba.size`

D. `mba.shape`

Answer: C. `mba.size`

Q12. A developer is working with the NumPy module. He wants to create a list with values ranging from 0 to 9 and print these values. He then wishes to hide the odd values and print only the even values (array masking). The code should print the following output:
[0 1 2 3 4 5 6 7 8 9]
[0 2 4 6 8]
Which of the following is the correct code snippet to do so?

A. 
```python
import numpy as n
val = n.range(10)
print(val)
m = (val%2 == 0)
print(val{m})
```

B. 
```python
import numpy as n
val = n.range(0..0)
print(val)
m = (val%2 == 0)
print(val[m])
```

C. 
```python
import numpy as n
val = n.arange(10)
print(val)
m= (val%2 == 0)
print(val[m])
```

D. 
```python
import numpy as n
val = n.nuRrange(0..9)
print(val)
m = (val%2 == 0)
print(val([m]))
```

Answer: C.
```python
import numpy as n
val = n.arange(10)
print(val)
m= (val%2 == 0)
print(val[m])
```

Q13. Which of the following is the correct syntax for creating a single tuple in Python?

A. `tu1 = (50,)`

B. `tu1 = ({50})`

C. `tu1 = (50;)`

D. Single tuple is not allowed in Python

**Answer: A. `tu1 = (50,)`**

 Q14. Consider a Python list named `a1` with the following values.

```python
a1 = [1, 23.5, 91, 'Orange', 'Apple', 'Butter', 222]
```

If a user wishes to remove the number value `91` from this list without using an index, then which of the following methods should be used?

A. `a1.pop(91)`

B. `a1.remove(91)`

C. `a1.delete(91)`

D. `a1.drop(91)`

**Answer: B. `a1.remove(91)`**

Q15. Mark wants to create a tuple in Python with values `14, 24, 5, 6.5, "Colour", "fruits"` and `"Objects"` in this order. He then wishes to print the type, the data type used (which is a tuple), the fourth value in the tuple, and then the first five values from the tuple, i.e., the following output:

```
6.5
(14, 24, 5, 6.5, 'Colour')
```

Which of the following is the correct code to do so?

A. 
```python
t1 = (14, 24, 5, 6.5, "Colour", "fruits", "Objects")
print(type.t1)
print(t1[4])
print(t1[1:5])
```

B. 
```python
t1 = (14, 24, 5, 6.5, "Colour", "fruits", "Objects")
print(datatype(t1))
print(t1[3])
print(t1[1-5])
```

C. 
```python
t1 = (14, 24, 5, 6.5, "Colour", "fruits", "Objects")
print(datatype(t1))
print(t1[4])
print(t1[0:5])
```

D. 
```python
t1 = (14, 24, 5, 6.5, "Colour", "fruits", "Objects")
print(type(t1))
print(t1[3])
print(t1[:5])
```

**Answer: D.**
```python
t1 = (14, 24, 5, 6.5, "Colour", "fruits", "Objects")
print(type(t1))
print(t1[3])
print(t1[:5])
```

Q16. What happens when the following Python code is compiled and executed?

```python
t1 = (6, 14, 15.2, 11.5, "Nina", "Lisa", "Mary")
t2 = (1, 2, 3, 4, 5)
t1 = t1 + t2
print(t1)
```

A. The code will compile successfully, and it will print the following output:
   ```
   (6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary', (1, 2, 3, 4, 5))
   ```

B. The code will throw an error as the + operator is not supported for tuples

C. The code will compile successfully, and it will print the following output:
   ```
   (1, 2, 3, 4, 5, 6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary')
   ```

D. The code will compile successfully, and it will print the following output:
   ```
   (6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary', 1, 2, 3, 4, 5)
   ```

**Answer: D.**
```
(6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary', 1, 2, 3, 4, 5)
```

Q17. What happens when the following Python code is compiled and executed?

```python
t1 = (6, 14, 15.2, 11.5, "Nina", "Lisa", "Mary")
t2 = (1, 2, 3, 4, 5)
t1 = t1 + t2
print(t1)
```

A. The code will compile successfully, and it will print the following output:
   ```
   (6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary', (1, 2, 3, 4, 5))
   ```

B. The code will throw an error as the + operator is not supported for tuples

C. The code will compile successfully, and it will print the following output:
   ```
   (1, 2, 3, 4, 5, 6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary')
   ```

D. The code will compile successfully, and it will print the following output:
   ```
   (6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary', 1, 2, 3, 4, 5)
   ```

**Answer: D.**
```
(6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary', 1, 2, 3, 4, 5)
```

Q18. Consider the following set named `myExample` in Python.

```python
myExample = set(["PQ", "RS", "TU", "VW"])
```

Which of the following commands would you use to remove all values from this set?

A. `myExample.discard()`

B. `myExample.clear()`

C. `myExample.remove()`

D. `myExample.drop()`

**Answer: B. `myExample.clear()`**

---

### Q19. While working on a Python program, a user needs to use a data structure that is unordered, indexed, and mutable. Also, this data structure should not allow duplicates.

Which of the following options should he use in this scenario?

A. `List`

B. `Dictionaries`

C. `Either set or dictionaries`

D. `Set`

**Answer: D. `Set`**

---

### Q20. A user declared the following set:

```python
a = set(["L", "M", "N", "O"])
```

If the user now needs to add two more values, "P" and "Q" to this set using a single command and then delete the value "M" from it, then which of the following syntaxes can be used?

A. 
```python
a.insert(["P", "Q"])
a.drop("M")
```

B. 
```python
a.add(["P", "Q"])
a.delete("M")
```

C. 
```python
a.update(["P", "Q"])
a.discard("M")
```

D. 
```python
a.extend(["P", "Q"])
a.pop("M")
```

**Answer: C.**
```python
a.update

(["P", "Q"])
a.discard("M")
```

---

These questions cover various aspects of Python programming, including data structures, libraries like Pandas and NumPy, and specific methods for handling data types such as tuples, lists, and sets. If you need any changes or additional information, please let me know!


Here are the questions formatted as a document with their corresponding answers:

---

**Q21. A user declared two sets in Python as follows:**

```python
a1 = set(["x", "y", "z"])
a2 = set([6, 8, 10])
```

Which of the following set operations will compile successfully for these two sets?

[i] `a2.add(12)`

[ii] `a1.add(5)`

[iii] `a2.add('L')`

[iv] `a1.add(a2)`

**Options:**

- i, ii, iii, and iv
- Only i
- Only i, ii, and iii
- Only i and iii

**Answer:** Only i and iii

---

**Q22. Which of the following is a finite loop in Python?**

**Options:**

- While
- Post
- None of these
- For

**Answer:** For

---

**Q23. Which of the following Python code snippets will compile?**

*Snippet 1:*
```python
colour = True
if colour:
    print(colour)
```

*Snippet 2:*
```python
colour = True
for colour:
    print(colour)
```

**Options:**

- Neither snippet 1 nor snippet 2 will compile
- Both, snippet 1 and snippet 2, will compile and print the output True
- Only snippet 1 will compile and print the output True
- Only snippet 2 will compile and print the output True

**Answer:** Only snippet 1 will compile and print the output True

---

**Q24. A programmer is dealing with a list of numbers: 2, 11, 13, 18, 21, 25, 33, 35, 40, and 42. He is required to write a program which will analyze each number in the list and print if it is even or odd.**

Which of the following is the correct code that will print the following output?

*Output:*
```
Even number
Odd number
Odd number
Even number
Odd number
Odd number
Odd number
Odd number
Even number
Even number
```

**Options:**

1. 
```python
a1 = [2, 11, 13, 18, 21, 25, 33, 35, 40, 42]
for i on a1:
    if (i%2 == 0):
        print("Even number")
    else:
        print("Odd number")
```

2.
```python
a1 = [2, 11, 13, 18, 21, 25, 33, 35, 40, 42]
for a1.i:
    if i%2 == 0:
        print("Even number")
    else:
        print("Odd number")
```

3.
```python
a1 = [2, 11, 13, 18, 21, 25, 33, 35, 40, 42]
for i in a1:
    if i%2 == 0:
        print("Even number")
    else:
        print("Odd number")
```

4.
```python
a1 = [2, 11, 13, 18, 21, 25, 33, 35, 40, 42]
for a1 use i:
    if (i%2 == 0)
        print("Even number")
    else
        print("Odd number")
```

**Answer:** Option 3

---

**Q25. Which of the following is the correct syntax for creating a single tuple in Python?**

**Options:**

- `tu1 = (50,)`
- `tu1 = ({50})`
- `tu1 = (50;)`
- Single tuple is not allowed in Python

**Answer:** `tu1 = (50,)`

---

**Q26. Consider a Python list named a1 with the following values.**

```python
a1 = [1, 23.5, 91, 'Orange', 'Apple', 'Butter', 222]
```

If a user wishes to remove the number value 91 from this list without using an index, then which of the following methods should be used?

**Options:**

- `a1.pop(91)`
- `a1.remove(91)`
- `a1.delete(91)`
- `a1.drop(91)`

**Answer:** `a1.remove(91)`

---

**Q27. Mark wants to create a tuple in Python with values 14, 24, 5, 6.5, "Colour", "fruits", and "Objects" in this order. He then wishes to print the type, the fourth value in the tuple, and the first five values from the tuple, i.e., the following output:**

```
6.5
(14, 24, 5, 6.5, 'Colour')
```

Which of the following is the correct code to do so?

**Options:**

1.
```python
t1 = (14, 24, 5, 6.5, "Colour", "fruits", "Objects")
print(type.t1)
print(t1[4])
print(t1[1:5])
```

2.
```python
t1 = (14, 24, 5, 6.5, "Colour", "fruits", "Objects")
print(datatype(t1))
print(t1[3])
print(t1[1-5])
```

3.
```python
t1 = (14, 24, 5, 6.5, "Colour", "fruits", "Objects")
print(datatype(t1))
print(t1[4])
print(t1[0:5])
```

4.
```python
t1 = (14, 24, 5, 6.5, "Colour", "fruits", "Objects")
print(type(t1))
print(t1[3])
print(t1[:5])
```

**Answer:** Option 4

---

**Q28. What happens when the following Python code is compiled and executed?**

```python
t1 = (6, 14, 15.2, 11.5, "Nina", "Lisa", "Mary")
t2 = (1, 2, 3, 4, 5)
t1 = t1 + t2
print(t1)
```

**Options:**

- The code will compile successfully, and it will print the following output:
  `(6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary', (1, 2, 3, 4, 5))`
- The code will throw an error as `+` operator is not supported for tuples
- The code will compile successfully, and it will print the following output:
  `(1, 2, 3, 4, 5, 6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary')`
- The code will compile successfully, and it will print the following output:
  `(6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary', 1, 2, 3, 4, 5)`

**Answer:** The code will compile successfully, and it will print the following output:  
`(6, 14, 15.2, 11.5, 'Nina', 'Lisa', 'Mary', 1, 2, 3, 4, 5)`

---

**Q29. Consider the following set named myExample in Python.**

```python
myExample = set(["PQ", "RS", "TU", "VW"])
```

Which of the following commands would you use to remove all values from this set?

**Options:**

- `myExample.discard()`
- `myExample.clear()`
- `myExample.remove()`
- `myExample.drop()`

**Answer:** `myExample.clear()`

---

**Q30. While working on a Python program, a user needs to use a data structure that is unordered, indexed, and mutable. Also, this data structure should not allow duplicates.**

Which of the following options should he use in this scenario?

**Options:**

- List
- Dictionaries
- Either set or dictionaries
- Set

**Answer:** Set

---

**Q31. A user declared the following set:**

```python
a = set(["L", "M", "N", "O"])
```

If the user now needs to add two more values, "P" and "Q" to this set using a single command and then delete the value "M" from it, then which of the following syntaxes can be used?

**Options:**

1. 
```python
a.insert(["P", "Q"])
a.drop("M")
```

2. 
```python
a.add(["P", "Q"])
a.delete("M")
```

3.
```python
a.update(["P", "Q"])
a.discard("M")
```

4.
```python
a.extend(["P", "Q"])
a.pop("M")
```

**Answer:** Option 3


### Q31. A user declared two sets in Python as follows:

```python
a1 = set(["x", "y", "z"])
a2 = set([6, 8, 10])
```

Which of the following set operations will compile successfully for these two sets?

[i] `a2.add(12)`

[ii] `a1.add(5)`

[iii] `a2.add('L')`

[iv] `a1.add(a2)`

A. i, ii, iii, and iv

B. Only i

C. Only i, ii, and iii

D. Only i and iii

**Answer: D. Only i and iii**

Explanation:
- `a2.add(12)` will compile successfully as it adds an integer to the set of integers.
- `a1.add(5)` will compile successfully but it's not shown in the options as `ii` and it's not valid here.
- `a2.add('L')` will compile successfully, adding a string to a set of integers.
- `a1.add(a2)` will raise an error because sets cannot contain other sets (they are unhashable).

---

### Q32. Which of the following is a finite loop in Python?

A. `While`

B. `Post`

C. None of these

D. `For`

**Answer: D. `For`**

Explanation:
- A `for` loop runs for a specific number of iterations, making it a finite loop.
- A `while` loop can be infinite if the condition never becomes false.

---

### Q33. Which of the following Python code snippets will compile?

**Snippet 1:**
```python
colour = True
if colour:
    print(colour)
```

**Snippet 2:**
```python
colour = True
for colour:
    print(colour)
```

A. Neither snippet 1 nor snippet 2 will compile

B. Both, snippet 1 and snippet 2, will compile and print the output `True`

C. Only snippet 1 will compile and print the output `True`

D. Only snippet 2 will compile and print the output `True`

**Answer: C. Only snippet 1 will compile and print the output `True`**

Explanation:
- **Snippet 1** is a valid `if` condition check and will print `True`.
- **Snippet 2** is invalid syntax; the `for` loop syntax is incorrect.

---

### Q34. A programmer is dealing with a list of numbers: `2, 11, 13, 18, 21, 25, 33, 35, 40, and 42`. He is required to write a program that will analyze each number in the list and print whether it is even or odd.

Which of the following is the correct code that will print the following output?

**Output:**
```
Even number
Odd number
Odd number
Even number
Odd number
Odd number
Odd number
Odd number
Even number
Even number
```

A. 
```python
a1 = [2, 11, 13, 18, 21, 25, 33, 35, 40, 42]
for i on a1:
    if (i%2 == 0):
        print("Even number")
    else:
        print("Odd number")
```

B. 
```python
a1 = [2, 11, 13, 18, 21, 25, 33, 35, 40, 42]
for a1.i:
    if i%2 == 0:
        print("Even number")
    else:
        print("Odd number")
```

C. 
```python
a1 = [2, 11, 13, 18, 21, 25, 33, 35, 40, 42]
for i in a1:
    if i%2 == 0:
        print("Even number")
    else:
        print("Odd number")
```

D. 
```python
a1 = [2, 11, 13, 18, 21, 25, 33, 35, 40, 42]
for a1 use i :
    if (i%2 == 0)
        print("Even number")
    else
        print("Odd number")
```

**Answer: C.**
```python
a1 = [2, 11, 13, 18, 21, 25, 33, 35, 40, 42]
for i in a1:
    if i%2 == 0:
        print("Even number")
    else:
        print("Odd number")
```


