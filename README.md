# asm-hex-to-dec

Написать функцию, выполняющую преобразование числа из шестнадцатеричной записи в десятичную.

Прототип функции:
`void hex_to_dec(char* dest, char* src);`

Входное шестнадцатеричное число 128-битное, со знаком в двоичном дополнительном коде. Перед числом может быть символ '-', который следует интерпретировать строго как "инвертировать все биты входного числа и добавить 1", что полезно для ввода отрицательных чисел. Буквы могут быть любого регистра.

В выходной буфер должна быть записана ноль-терминированная строка результата без переводов строки или ещё каких-либо лишних символов.

Конвенция вызова: `cdecl`. Функция должна быть реализована в `hex_to_dec.asm`.

В репозитории есть файл `main.c`, предназначенный для простого тестирования.