# assignment-15-python
python
def unique_numbers(duplicate): 
   # converting list to set to store unique values 
   unique_numbers_set = set(duplicate) 
   # converting the set back to a list 
   unique_numbers_list = list(unique_numbers_set) 
   return unique_numbers_list

duplicate_list = [1, 2, 3, 4, 1, 2, 5, 6, 6, 6] 
print(unique_numbers(duplicate_list))
