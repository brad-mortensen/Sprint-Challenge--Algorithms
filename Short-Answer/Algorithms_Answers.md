Add your answers to the Algorithms exercises here.

Exercise I:

a) O(n)

b) O(n^4)

c) O(1)

Exercise II:

def egg_drop_test(n, f):
    Start by setting the drop point at n/2 and dropping. 
    if the egg breaks, recursively call the function again with n/2 as the drop floor
    until you find a floor that doesnt break the egg
    
This algorithm would run O(log n)    
