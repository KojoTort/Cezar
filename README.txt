English:
	Caesar Cipher Library Documentation
Introduction
The Caesar Cipher Library is a Python library that provides a simple implementation of the Caesar Cipher encryption and decryption algorithms. The library allows you to easily encrypt and decrypt text using the Caesar Cipher method.

Functions
encrypt(text, shift)
Encrypts the given text using the Caesar Cipher method with the specified shift value.

Parameters:

text: The text to be encrypted (string)
shift: The shift value to use for encryption (integer)
Returns:

The encrypted text (string)
Example:
encrypted_text = caesar_cipher.encrypt("Hello, World!", 3)
print(encrypted_text)  # Output: Khoor, Zruog!
decrypt(text, shift)
Decrypts the given text using the Caesar Cipher method with the specified shift value.

Parameters:

text: The text to be decrypted (string)
shift: The shift value to use for decryption (integer)
Returns:

The decrypted text (string)
Example:
decrypted_text = caesar_cipher.decrypt("Khoor, Zruog!", 3)
print(decrypted_text)  # Output: Hello, World!
execute_cs_code(cs_code, shift)
Decrypts the given cs_code using the Caesar Cipher method with the specified shift value, and then executes the decrypted code as Python code.

Parameters:

cs_code: The Caesar Cipher code to be decrypted and executed (string)
shift: The shift value to use for decryption (integer)
Returns:

None
Example:
cs_code = """
khoor, zruog!
cnjuf(khoor + ', ' + zruog + '!')
"""

shift_value = 3

caesar_cipher.execute_cs_code(cs_code, shift_value)
This will decrypt the Caesar Cipher code and execute it as Python code.

How it Works
The Caesar Cipher Library uses the following algorithm to encrypt and decrypt text:

Iterate through each character in the input text.
If the character is a letter (either uppercase or lowercase), shift it by the specified shift value.
If the character is not a letter, leave it unchanged.
Return the resulting encrypted or decrypted text.
The execute_cs_code function decrypts the input Caesar Cipher code using the decrypt function, and then executes the decrypted code as Python code using the exec function.

Limitations
The Caesar Cipher Library has the following limitations:

It only works with ASCII characters.
It does not handle non-English characters or special characters.
It is not secure for encrypting sensitive information, as the Caesar Cipher method is easily breakable.
License
The Caesar Cipher Library is licensed under the MIT License. See the LICENSE file for details.

Author
The Caesar Cipher Library was written by [KojoTort].

Russian:
	Документация к библиотеке Caesar Cipher
Введение
Библиотека Caesar Cipher - это библиотека на языке Python, которая предоставляет простую реализацию алгоритмов шифрования и дешифрования методом Цезаря. Библиотека позволяет легко шифровать и дешифровать текст с помощью метода Цезаря.

Функции
encrypt(text, shift)
Шифрует заданный text с помощью метода Цезаря с указанным значением shift.

Параметры:

text: Текст, который нужно шифровать (строка)
shift: Значение сдвига для шифрования (целое число)
Возвращает:

Зашифрованный текст (строка)
Пример:

encrypted_text = caesar_cipher.encrypt("Привет, Мир!", 3)
print(encrypted_text)  # Output: Хоор, Зруог!
decrypt(text, shift)
Дешифрует заданный text с помощью метода Цезаря с указанным значением shift.

Параметры:

text: Текст, который нужно дешифровать (строка)
shift: Значение сдвига для дешифрования (целое число)
Возвращает:

Дешифрованный текст (строка)
Пример:
decrypted_text = caesar_cipher.decrypt("Хоор, Зруог!", 3)
print(decrypted_text)  # Output: Привет, Мир!
execute_cs_code(cs_code, shift)
Дешифрует заданный cs_code с помощью метода Цезаря с указанным значением shift, а затем выполняет дешифрованный код как код Python.

Параметры:

cs_code: Код Цезаря, который нужно дешифровать и выполнить (строка)
shift: Значение сдвига для дешифрования (целое число)
Возвращает:


Пример:
cs_code = """
хоор, zruog!
cnjuf(khoor + ', ' zruog + '!')
"""

shift_value = 3

caesar_cipher.execute_cs_code(cs_code, shift_value)
Это дешифрует код Цезаря и выполняет его как код Python.

Как это работает
Библиотека Caesar Cipher использует следующий алгоритм для шифрования и дешифрования текста:

Итерируемся по каждому символу в входном тексте.
Если символ является буквой (либо в верхнем, либо в нижнем регистре), сдвигаем его на указанное значение shift.
Если символ не является буквой, оставляем его без изменений.
Возвращаем полученный зашифрованный или дешифрованный текст.
Функция execute_cs_code дешифрует входной код Цезаря с помощью функции decrypt, а затем выполняет дешифрованный код как код Python с помощью функции exec.

Ограничения
Библиотека Caesar Cipher имеет следующие ограничения:

Она работает только с символами ASCII.
Она не обрабатывает неанглийские символы или спецсимволы.
Она не является безопасной для шифрования чувствительной информации, поскольку метод Цезаря легко взламывается.
Лицензия
Библиотека Caesar Cipher лицензирована под лицензией MIT. См. файл LICENSE для подробностей.

Автор
Библиотека Caesar Cipher была написана [KojoTort].