string = input("Введите строку: ")
vowels = "aeiou"
count = 0
for char in string:
    if char.lower() in vowels:
        count += 1
print("Количество гласных:", count)
