# Запит користувача на введення 4-хзначного числа
user_input = input("Введіть 4-хзначне число: ")

# Перевірка на правильність введеного числа
if len(user_input) != 4 or not user_input.isdigit():
    print("Будь ласка, введіть правильне 4-хзначне число.")
else:
    # Розділення числа на цифри та виведення їх в стовпчик
    for digit in user_input:
        print(int(digit))
