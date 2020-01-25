# Conditions and Branching and Logical Operators

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
    print('you can enter') #the true statement is used by writing code as an indent, away from the side
print('move on')#this statement will run regardless of whether the statement is true or not

#ElSE Statement exmaple 

age = 17
if age > 18:
    print('you can enter')
else: #the else statement runs a block of code if none of the conditions before it are true
    print('go home')
print('and move on')

#ELIF statement - allows us to check additional conditions if the condition statements before it are FALSE

age = 17
if age > 18:
    print('you can enter')
elif age == 17:  
    print('bugger off to somewhere in America')
else:
    print('go home')
print('and move on')    

#Logical operators - used to check multiple conditions at once

# they are: and, or, not

#using the AND operator to check two coniditons

age = 19
if(age > 18) and (age < 26):
    print('you are the correct age for this')
print('please go on through')

#using the OR operator

album_age = 1984
if(album_age < 1980) or (album_age > 1989):
    print('the album was released not in the 80s')
else:
    print('the album was released in the 1980s')
    
#using the NOT operator
album_age = 1984
if not(album_age == '1983'):
    print('the album was not released in 1983')


