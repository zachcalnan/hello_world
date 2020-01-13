Sets

set1 = {"pop", "rock", "soul", "hard rock", "rock", "R&B", "rock", "disco"}

#List into a set

Zach = ("pop", "rock", "soul", "hard rock", "rock", "R&B", "rock", "disco")
set = set(Zach)
print(set)

#adding or removing from to a set

Zach = ("pop", "rock", "soul", "hard rock", "rock", "R&B", "rock", "disco")
set = set(Zach)
set.add('added item')
print(set)

or

Zach = ("pop", "rock", "soul", "hard rock", "rock", "R&B", "rock", "disco")
set = set(Zach)
set.remove('added item')
print(set)

#using the IN function to verify if an element is in a set

Zach = ("pop", "rock", "soul", "hard rock", "rock", "R&B", "rock", "disco")
set = set(Zach)
print('rock'in set)

#using the & function to find the intersect 

album_set1 = set(["Thriller", 'AC/DC', 'Back in Black'])
album_set2 = set([ "AC/DC", "Back in Black", "The Dark Side of the Moon"])
intersection = album_set1 & album_set2
print(intersection) 

#to find the difference in data sets use the .difference function

album_set1 = set(["Thriller", 'AC/DC', 'Back in Black'])
album_set2 = set([ "AC/DC", "Back in Black", "The Dark Side of the Moon"])
intersection = album_set1 & album_set2
print(album_set1.difference(album_set2)) 

#intersection of two circles can be found also with the below .intersection function

album_set1.intersection(album_set2)   

#union contains all elements within both of the circles

album_set1.union(album_set2)

#to see if one circle is a subset ot superset of another circle use the following functions

set(album_set1).issuperset(album_set2)   
set(album_set2).issubset(album_set1)   
