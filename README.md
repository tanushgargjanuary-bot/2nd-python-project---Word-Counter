# 2nd-python-project---Word-Counter
Made another ugly project, slowly learning new concepts while building
The end goal output is the program must show, Number of Character(spaces included), Number of Words, Number of Vowels, after the user inputs a valid string/ sentence.

WHAT I LEARNED: 
Splitting sentence with split function, 
Counting vowels 

	count = 0
	vowels = "AEIOUaeiou" # <---- This is the main component for logic
	for i in sentence:
		if i in vowels:
			count += 1
	print(f"There are {count} vowels")
