# Reading and writing files.
#the open function is used to correspond to a file.
#'r' is used to read, 'w' is used to chnage the file, 'a' is used to apend onto the end of the file, 'r+' is used to read and write  

#the below example is used if we were reading from a file called employee.txt

employee_file = open('employee.txt', 'r') #this opens the file
print(employee_file.read()) #.read is used to pull the data from the file
employee_file.close() # this is used to close a file.


#To write into a file use the 'w'

with open('ghost.txt', 'w') as f:
   f.write('test') #this will create a txt file with 'test written in it
