## How to find if the K-th bit of a binary number is set(1) or not?

      >> leftshift 1 for k-1 times
    
      >> AND it with the given number
      
      >> if the result = 0
         then K-th bit is NOT set i.e. 0
         and 
         if the result != 0
         then K-th bit is set i.e. 1.
