# Python

import random
import time

answer = random.randint(1,15)

time1 = time.time()

while True:
	choice = int(input(""))
	if choice < answer:
		print ("The Number is too low!")
	elif choice > answer:
		print ("The Number is too high")
	elif choice == answer:
		break
print ("You've guessed the Right Number!!!Congratulations!!!!")

time2 = time.time()

totalTime =  str(int(time2 - time1))

print ("It took you "  +  totalTime +   " seconds.")
