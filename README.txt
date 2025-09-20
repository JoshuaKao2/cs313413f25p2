TestIterator
Question: Also try with a LinkedList - does it make any difference?
- it still works, there is no difference in execution
Question: What happens if you use list.remove(Integer.valueOf(77))?
- exception error


TestList
Question: Also try with a LinkedList - does it make any difference?
- it still works, theres no difference in execution
list.remove(5); //  Question: What does this method do?
- it removes the value at index 5
list.remove(Integer.valueOf(5)); //  What does this method do?
- it removes the value 5 from the list

TestPerformance
- as size increases, LinkedList is faster at adding and removing
- as size increases, ArrayList is faster at indexing a value
- for the task that it is faster for, each one still performed very quickly, (less than second-few seconds) 
- while when performing the slower task, took a lot more time (tens of seconds)
