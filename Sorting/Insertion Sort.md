# Insertion Sort

### Complexity : O(n^2)

We have to assume that there's a sorted list and an unsorted list in the given list or array.
Each and every time we will get an element from the unsorted list and place it in the appropriate position in the sorted list.
If we take only 1st element from the given list then it is already sorted. So initially 1st element is the Sorted list and rest are in the unsorted list.

### Algorithm :

          1. Construct a loop from 2nd element to the last one to traverse the unsorted list.
          
          2. Get an element from the unsorted list (one by one) and reserve it in a temporary/key variable.
         
          3. Repeat 4 & 5 While KEY is smaller than the elemnts of sorted list.
         
          4. Compare the Temp/Key variable with the elements from the unsorted list from position (key-1)th to 0th
         
          5. If Key is smaller then move the sorted elements one place later.
         
          6. When Key is not smaller than an element of sorted list, it's the correct position for the Key.
             So place the Key in that position where the loop has stopped.
    
