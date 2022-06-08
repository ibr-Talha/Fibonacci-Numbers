# Fibonacci-Numbers

fibonacci = []
firstNumber = 0
secondNumber = 1
people_range = int(input("Kaç Defa Dönsün>>>>> "))
if people_range ==1:
  print(firstNumber)

for i in range(2,people_range):

  toplam = firstNumber
  firstNumber += secondNumber
  secondNumber = toplam
  fibonacci.append(firstNumber)

print(fibonacci," ", end="")
