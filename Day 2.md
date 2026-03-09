username = input("Wite your name:")

username

alphabet=  input("Enterasinglealphabetcharacter:")

if alphabet in "aeiouAEIOU":
  print("alphabate is vowel")

else:
  print('not a vowel')


if alphabet.lower() in "aeiou":
  print("")

alphabet = input("enter a symbol: ")

if alphabet.isalpha():
  print("symbol is alphabet")
else:
  print("symbol is not an alphabet")

list1 = ["Arya",2,1.2]
for i in list1:
  print (i)

i = 0
while i < 5:
  print(i)
  i += 1

list2 = ["one","two",1,2,"string"]
for i in list2:
  if str(i).isalpha():
    print(i)
  else:
    continue

i = 1
while i < len(list2):
  print(list2[i])
  i += 2

"string"
