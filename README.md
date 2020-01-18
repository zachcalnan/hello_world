# Dictonaries

#Creating a dictionary 

Dict = {"key1": 1, "key2": "2", "key3": [3, 3, 3], "key4": (4, 4, 4), ('key5'): 5, (0, 1): 6}
print(Dict)

#access a certain value of a key 

Dict = {"key1": 1, "key2": "2", "key3": [3, 3, 3], "key4": (4, 4, 4), ('key5'): 5, (0, 1): 6}
print(Dict["key1"])

#we can gain access to a Dectionaries values by doing the following 

release_year_dict = {"Thriller": "1982", "Back in Black": "1980", \
                    "The Dark Side of the Moon": "1973", "The Bodyguard": "1992", \
                    "Bat Out of Hell": "1977", "Their Greatest Hits (1971-1975)": "1976", \
                    "Saturday Night Fever": "1977", "Rumours": "1977"}
print(release_year_dict['Thriller'])              

#get all of the keys in the dictionary

print(release_year_dict.keys())

#get all of the vlaues in a dictionary

print(release_year_dict.values())

#adding an entry

release_year_dict['Zach is a complete G']='2020'
print(release_year_dict)

#delting an entry 

del(release_year_dict['Thriller'])
print(release_year_dict)
                
#verifying an element is in the dictionary

print('The Bodyguard' in release_year_dict)


