# prime-number-calculation. 
# A prime number is a number that is divisible only by itself and 1 (e.g. 2, 3, 5, 7, 11).
# This program calculates all the prime numbers less or equal to a given maximum integer.
# This is a python program to generate a quick list of prime numbers.
# The program will ask you to type an upper limit for the prime number calculations.
# If you type: 10 the program will return [2,3,5,7] 
# If you type: 1000 the program will return all the prime numbers less than 1000 [2,3,.....991,997]
# How does this program performs the prime number calculation?
# it reads your maximum integer input and stores this in max
# max = int(input())
# Next it creates an empty list.
# primeList=[]
# Next it starts a loop in the range from 2 to max+1
# for x in range(2, max+1):
# max+1 and not max because if the maximum input for example would be 7 it would return [2,3,5] instead of [2,3,5,7]
# Next it initiates the boolean isPrime as true.
# The loop checks if a number x is a prime number by dividing it by all numbers in the range (2,x) and check if the remainder of the division is not zero.
# If one of the remainders of the divisions returns zero the loop stops to save calculation time (break)
# for x in range(2, max+1):
#     isPrime = True
#     for y in range (2,x):
#         if x%y == 0:
#            isPrime = False
#            break
#  
# If the boolean isPrime stayes true for all the divisions, it appends this value x to the list primeList because this x is a prime number.
#     if isPrime:
#         primeList.append(x)
# Next it prints all the prime numbers stored in the list primeList.
# print(primeList)




