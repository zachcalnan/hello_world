# Conditions and Branching

#Comparison operations compare some value or operand and, based on a condition

equal: ==
not equal: !=
greater than: >
less than: <
greater than or equal to: >=
less than or equal to: <=

# Branching allows us to run different inputs for different statements 

#IF Statement example

age = 19
if age > 18:
    print('you can enter') #the true statmeent is used by writing code as an indent, away from the side
print('move on')#this statement will run regardless of whether the statement is true or not

#ElSE Statement exmaple 

age = 17
if age > 18:
    print('you can enter')
else: #the else statement runs a block of code if none of the conditions before it are true
    print('go home')
print('and move on')


  


