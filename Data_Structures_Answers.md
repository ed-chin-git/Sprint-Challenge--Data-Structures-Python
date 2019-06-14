
REFERENCE:  https://wiki.python.org/moin/TimeComplexity

Add your answers to the questions below.

1. What is the runtime complexity of your ring buffer's `append` method?   O(1)   1 If 

2. What is the space complexity of your ring buffer's `append` function?   O(1)  does not allocate more memory when appending

3. What is the runtime complexity of your ring buffer's `get` method?    O(n)   1 loop and 1 If

4. What is the space complexity of your ring buffer's `get` method?  O(n)  'n' values in list_out.


5. What is the runtime complexity of the provided code in `names.py`?  O(n^2)  2 nested loops

6. What is the space complexity of the provided code in `names.py`?  O(n/2)  
     worst case scenario:  all items in list 1 are duplicated in list 2. If 20,000 names, duplicate list =10,0000 ( 20,000 / 2 ).

7. What is the runtime complexity of your optimized code in `names.py`?  O(n)   
   According to Python wiki: Time complexity, set is implemented as a hash table.  
                                                      
   set operation: INTERSECTION of s and t        
    Average case :  O(min(len(s), len(t))  
     Worst case  :  O(len(s) * len(t))

8. What is the space complexity of your optimized code in `names.py`? O(n)
