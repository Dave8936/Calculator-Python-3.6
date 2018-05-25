# Calculator-Python-3.6

print("Choose your first number")
number1 = int(input())
print("Choose your second number")
number2 = int(input())
print("1 - Add")
print("2 - Subtract")
print("3 - Multiply")
print("4 - Divide")
print("5 - Power")

print("Which operation would you like to choose?")
chosen_menu = input()

if chosen_menu == '1':
    print(number1 + number2)
elif chosen_menu == '2':
    print(number1 - number2)
elif chosen_menu == '3':
    print(number1 * number2)
elif chosen_menu == '4':
    print(number1 / number2)
elif chosen_menu == '5':
    print(number1 ** number2)
else
    print("Invalid option selected")
