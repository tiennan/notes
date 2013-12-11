## My Python note

ref: [Dive into python](http://woodpecker.org.cn/diveintopython/)

### Boolean

    True / False # First letter is capitalized
    
### Dictionary
 - Dictionary in C#
 - HashTable in Java
 - {} in Javascript

Code:

    d = {'key': 'value'}
    del d['key']        # delete item with specific 'key'
    d.clear()           # clear all items in dictionary

### List
 - ArrayList in Java

Code:

    li = ['a', 'b', 'c', 'd', 'e']
    li[1:3]               # ['b', 'c']
    li[1:-1]              # ['b', 'c', 'd']
    li[3:]                # ['d', 'e']
    li[:3]                # ['a', 'b', 'c']
    li.append('F')        # ['a', 'b', 'c', 'd', 'e', 'F']
    li.insert(2, 'G')     # ['a', 'b', 'G', 'c', 'd', 'e', 'F']
    li.extend(['H', 'I']) # ['a', 'b', 'G', 'c', 'd', 'e', 'F', 'H', 'I']
    len(li)               # 9
    li.index('c')         # 3
    li.index('gg')        # throw ValueError: 'gg' is not in list
    li.remove('H')        # ['a', 'b', 'G', 'c', 'd', 'e', 'F', 'I'] // remove first 'H'
    'a' in li             # True
    'H' in li             # False
    li.pop()              # 'I' // remove last item and return it's value
    [1, 2] + [3, 4]       # [1, 2, 3, 4] // like extend, but return a new list
    li = [1,2] * 3        # [1, 2, 1, 2, 1, 2]

### Tuple
 - Tuple == constant(read only) List
 - No methods in tuple
 - Can be a key in dictionary

Code:

    t = ('a', 'b', 'c', 'd')
    list(t)              # [1, 2, 3, 4] // tuple -> list
    tuple(t)             # (1, 2, 3, 4) // list -> tuple
    

    
    
    
    
    
    
    
    
    
    
    
