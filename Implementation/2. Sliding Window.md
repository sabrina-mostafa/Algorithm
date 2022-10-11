# Sliding Window
### maximum valued subarray of size, k = 4 :
      i) sum = add 1st 4 elements
     ii) Check max sum for all i, j :
            i=1, j=k+1 ;
            sum - a[i] + a[j] ;
            i++, j++ ;
