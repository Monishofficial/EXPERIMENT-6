# EXPERIMENT-6

## AIM
### To write a Python program for checking Palindrome and to write test cases for ir. 

## ALGORITHM
Step 1: Start

Step 2: Get an input from the user by prompting

Step 3: Run a loop form 0 to len/2.

Step 4: Check if the characters are the same both from the start and the end till len/2.

Step 5: If it is, return the result that it is a palindrome.

Step 6: Else, return that it is not a palindrome.

Step 7: Stop. 

## PROGRAM
### NAME: MONISH N
### REGNO: 212223240097
~~~
def Palindrome(string):
    for i in range(0, int(len(string) / 2)):
        if string[i] != string[len(string) - i - 1]:  # Fixed indexing
            return False
    return True


s = input("Enter a string: ")  # Added a prompt for clarity

c = 1
for i in s:
    if not i.isalpha():
        c = 0
        break  # Added break to stop checking after finding a non-alphabetic character

if c == 0:
    print("Enter a valid string")
    print("Test Case:Fail")
else:
    answer = Palindrome(s)
    if answer:
        print("The given string is a palindrome")
        print("Test Case:Pass")
    else:
        print("The given string is not a palindrome")
        print("Test Case:Pass") 

~~~

## OUTPUT

Alphanumeric values:

<img width="687" height="93" alt="image" src="https://github.com/user-attachments/assets/23ac8502-ee08-47a1-85f6-d52cffb20026" />

Numeric values:

<img width="675" height="88" alt="image" src="https://github.com/user-attachments/assets/b75066bb-400c-425f-a74c-720462586cb6" />


Alphabet values:

<img width="598" height="74" alt="image" src="https://github.com/user-attachments/assets/a6a40b8b-e22b-42ab-be80-9ed79f9efcc6" />

Non-palindrome string:

<img width="648" height="89" alt="image" src="https://github.com/user-attachments/assets/bb4a3dab-a0ec-47ab-8b9c-4e67b72dfad0" />


Symbols:

<img width="630" height="90" alt="image" src="https://github.com/user-attachments/assets/152434ee-e8f3-46c8-b47b-01895cfc80d1" />


## RESULT
Thus, a program to check palindrome has been written and test cases have been written and verified
successfully. 
