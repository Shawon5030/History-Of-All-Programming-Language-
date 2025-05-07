
# 🐍 Python: 100 Essential Methods and Functions

A curated list of 100 essential Python methods and functions, complete with descriptions and usage examples. This compilation serves as a valuable reference for developers seeking to deepen their understanding of Python's capabilities.

---

## 📌 Table of Contents

- [1. Built-in Functions](#1-built-in-functions)
- [2. String Methods](#2-string-methods)
- [3. List Methods](#3-list-methods)
- [4. Dictionary Methods](#4-dictionary-methods)
- [5. Set Methods](#5-set-methods)

---

## 1. Built-in Functions

```python
1. abs(-7)                          # Output: 7
2. all([True, True, False])        # Output: False
3. any([False, False, True])       # Output: True
4. bin(5)                           # Output: '0b101'
5. bool(0)                          # Output: False
6. chr(97)                          # Output: 'a'
7. divmod(8, 3)                     # Output: (2, 2)
8. list(enumerate(['a', 'b', 'c'])) # Output: [(0, 'a'), (1, 'b'), (2, 'c')]
9. eval('2 + 3')                    # Output: 5
10. list(filter(lambda x: x > 0, [-2, 0, 1, 2]))  # Output: [1, 2]
11. float('3.14')                   # Output: 3.14
12. format(255, 'x')                # Output: 'ff'
13. hex(255)                        # Output: '0xff'
14. id(5)                           # Output: memory address
15. int('10')                       # Output: 10
16. isinstance(5, int)              # Output: True
17. len("Hello")                    # Output: 5
18. list(range(5))                  # Output: [0, 1, 2, 3, 4]
19. max([1, 2, 3])                  # Output: 3
20. min([1, 2, 3])                  # Output: 1
```

## 2. String Methods

```python
21. 'hello'.capitalize()           # Output: 'Hello'
22. 'HELLO'.casefold()             # Output: 'hello'
23. 'hi'.center(5, '*')            # Output: '**hi*'
24. 'banana'.count('a')            # Output: 3
25. 'hello'.encode()               # Output: b'hello'
26. 'python'.endswith('on')        # Output: True
27. 'abc\ndef'.expandtabs()        # Output: 'abc\ndef'
28. 'HELLO'.lower()                # Output: 'hello'
29. 'hello'.upper()                # Output: 'HELLO'
30. 'Python is fun'.replace('fun', 'awesome') # Output: 'Python is awesome'
```

## 3. List Methods

```python
31. lst = [1, 2]; lst.append(3)    # lst becomes [1, 2, 3]
32. lst.clear()                    # lst becomes []
33. lst = [1, 2]; lst.copy()       # Output: [1, 2]
34. [1, 2, 2, 3].count(2)          # Output: 2
35. lst = [1, 2]; lst.extend([3])  # lst becomes [1, 2, 3]
36. lst.index(2)                   # Output: 1
37. lst.insert(1, 'a')             # lst becomes [1, 'a', 2]
38. lst.pop()                      # Removes last element
39. lst.remove('a')                # Removes 'a' from list
40. lst.reverse()                  # Reverses list
```

## 4. Dictionary Methods

```python
41. d = {'a': 1}; d.clear()              # d becomes {}
42. d = {'a': 1}; d.copy()               # Output: {'a': 1}
43. dict.fromkeys(['a', 'b'], 0)         # Output: {'a': 0, 'b': 0}
44. d.get('a')                           # Output: 1
45. list(d.items())                      # Output: [('a', 1)]
46. list(d.keys())                       # Output: ['a']
47. d.pop('a')                           # Removes key 'a'
48. d.setdefault('b', 2)                 # Adds 'b' with 2 if not exists
49. d.update({'c': 3})                   # Updates with new key
50. list(d.values())                     # Output: values of dict
```

## 5. Set Methods

```python
51. s = {1, 2}; s.add(3)                 # s becomes {1, 2, 3}
52. s.clear()                            # s becomes set()
53. s.copy()                             # Output: {1, 2}
54. {1, 2, 3}.difference({2, 3})         # Output: {1}
55. s.discard(2)                         # s becomes {1}
56. {1, 2}.intersection({2, 3})          # Output: {2}
57. {1, 2}.issubset({1, 2, 3})           # Output: True
58. {1, 2}.issuperset({1})               # Output: True
59. {1, 2, 3}.pop()                      # Removes arbitrary element
60. {1, 2}.union({3, 4})                 # Output: {1, 2, 3, 4}
```

## 6. File Methods

```python
61. open('file.txt', 'r')               # Opens file for reading
62. open('file.txt', 'w')               # Opens file for writing
63. f = open('file.txt'); f.read()      # Reads content
64. f.readline()                        # Reads a line
65. f.readlines()                       # Reads all lines
66. f.write("Hello")                    # Writes to file
67. f.writelines(['Hi\n', 'Hello'])    # Writes lines
68. f.seek(0)                           # Moves cursor to start
69. f.tell()                            # Tells current position
70. f.close()                           # Closes file
```

## Additional Utilities and Concepts (71–100)

```python
71. zip([1, 2], ['a', 'b'])             # Output: [(1, 'a'), (2, 'b')]
72. map(str, [1, 2])                    # Output: ['1', '2']
73. sorted([3, 1, 2])                   # Output: [1, 2, 3]
74. reversed([1, 2, 3])                 # Output: [3, 2, 1]
