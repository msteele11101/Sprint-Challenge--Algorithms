#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) the amount of times the loop will run depends on the value of n.


b)first loop time complexity is O(n), but the the second loop run for almost half of the value of n. so total runtime complexity would be O(nlogn).  


c)O(n). The function will run in relation of value of n

## Exercise II

1 start from the middle floor f = n//2,
2 then you would drop a egg
3 check if the egg is broken or not...
4 if egg is broken repeat the same process for the left subarray of n//2(0 to f-1)
5 if egg is not broken repeat the process for the right subarray of n//2(f+1, n)
 Repeat step 1 to 5 until n = 0 or n= n
 Runtime complexity for this solution will be O(nlogn)
