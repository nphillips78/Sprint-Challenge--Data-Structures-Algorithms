Add your answers to the Algorithms exercises here.
I.
A. O(n)
B. O(n^3)
C. O(n)

II.
1. First, drop egg from floor f/2. 
2a. If it **doesn't** break, new f = (top floor - current floor)/2 and drop egg.
2b. If it **does** break, new f = (current floor - bottom floor)/2 and drop egg.
3. Repeat step 2a or 2b until only one floor is left.