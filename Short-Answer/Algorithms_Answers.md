#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)

O(n)

b)

O(n^2)

c)

O(n)
## Exercise II
First-pass option:
While on first floor, drop 1 egg.
Retrieve that egg.
Go up by one floor until you break an egg and then subtract 1.
Result: Floor found with only 1 egg broken.
o(n)

Other option:
Start halfway up. 
Process to loop through:
Drop 1 egg.
If it breaks, go to halfway of halfway and the first floor (or 1 quarter of total building)
Else if it doesn't break, go halfway between halfway and the top (or 3 quarters of the total building)
Repeat process until you find the floor.
o(log(n))

