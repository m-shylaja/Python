# Python Interview questions and Coding answers

Generator: Type of Interator, it iterates the item without storing in memory
Example: 
def count_no(n):
  i = 1
  while i<=n:
    yeild i
    i +=1
gen = count_no(5)
for num in gen:
  print(num)


Lambda: Anonymous, small, inline function, mutiple arguments but one experssion.
Example:
square = lambda x: x**2
print(square(4))

