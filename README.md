def bank(a, years):
    for _ in range(years):  # Повторяем увеличение вклада 'years' раз
        a *= 1.1  # Увеличиваем сумму на 10%
    return round(a, 2)  # Округляем до 2 знаков после запятой

# Примеры вызова функции
print(bank(777, 15))  # Начальный вклад 777 рублей, срок 15 лет
print(bank(5000, 5))  # Начальный вклад 5000 рублей, срок 5 лет# python-homework
