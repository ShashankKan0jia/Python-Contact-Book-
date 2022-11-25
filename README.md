# Python-Contact-Book-
#In this project, I made a python program which can work as a contact book or can be used to read, edit, save and delete contact names. 


names = []
phone_numbers = []

num = int(input("Enter the no. of repository"))

for i in range(num):
    name = input("Enter Name: ")
    phone_number = input("Enter Phone Number: ")

    names. append(name)
    phone_numbers.append(phone_number)

print("\tName\t\t\tPhone Number")

for i in range(num):
    print(f'\t{names[i]}\t\t\t{phone_numbers[i]}')


S = input("Enter the Name to search: ")
if S in names:
    index = names.index(S)
    name = names[index]
    phone_number = phone_numbers[index]

    print(f"Name:{name} , Phone number:{phone_number}")
else:
    print("Name not found!")
