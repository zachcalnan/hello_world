# Objects & Classes

class Zach: #set the class 
    def introduce_self(self): # this is a function, make sure to add the additional arguments 'self' 
        print('My name is ' + self.name, 'I like the colour ' + self.colour)

r1 = Zach() #this is a new objcet with the class Zach 
r1.name = 'Zach'    #this is how to set the attibutes
r1.colour = 'Red'
r1.weight = 155

r1.introduce_self() #this is how to run this function 
