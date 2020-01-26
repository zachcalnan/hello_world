#Loops

# FOR Loops - allow you to execute a block code multiple times

dates = [1982, 1980, 1973]
N = len(dates)
for i in range(N):
    print(dates[i])
    
#printing out a sequence in numbers

for i in range(0, 8):
   print(i) #
   
# Use for loop to change the elements in list

squares = ['red', 'yellow', 'green', 'purple', 'blue']

for i in range(0, 5):
    print("Before square ", i, 'is',  squares[i])
    squares[i] = 'weight'
    print("After square ", i, 'is',  squares[i])
    
# how to access the index and the elements of a list as follows    
    
squares=['red', 'yellow', 'green', 'purple', 'blue']

for i, square in enumerate(squares):
    print(i, square)
    
#While loop - used to keep executing code until a certian condiiton is not met

dates = [1982, 1980, 1973, 2000]

i = 0
year = 0

while(year != 2000):
    year = dates[i]
    i = i + 1
    print(year)

print("It took ", i, "repetitions to get out of loop.")
