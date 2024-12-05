<h1>Задание №3</h1>

**Вариант №6**

Разработать инструмент командной строки для учебного конфигурационного языка, синтаксис которого приведен далее. Этот инструмент преобразует текст из входного формата в выходной. Синтаксические ошибки выявляются с выдачей сообщений.
Входной текст на учебном конфигурационном языке принимается из файла, путь к которому задан ключом командной строки. Выходной текст на языке xml попадает в файл, путь к которому задан ключом командной строки.

Однострочные комментарии:

:: Это однострочный комментарий

Многострочные комментарии:

{ 

Это многострочный 

комментарий 

}

Словари:

table( имя => значение, 

имя => значение, 

имя => значение, 

... 

)

Имена:

[_a-z]+

Объявление константы на этапе трансляции:

имя = значение

Вычисление константного выражения на этапе трансляции (префиксная форма), пример:

[+ имя 1]

Результатом вычисления константного выражения является значение.

Для константных вычислений определены операции и функции:

1. Сложение.
   
2. Вычитание.
   
3. Умножение.
   
4. Деление.
   
5. pow().
   
Все конструкции учебного конфигурационного языка (с учетом их возможной вложенности) должны быть покрыты тестами. Необходимо показать 3 примера описания конфигураций из разных предметных областей.

<h2>Описание функций</h2>

•**evaluate_prefix(expression, constants)** - Функция для вычисления префиксного выражения

•**remove_comments(text)** - Функция для удаления комментариев

•**parse_constants(text)** - Функция для парсинга объявления константы

•**parse_dict(text, constants)** - Функция для парсинга словаря

•**to_xml(constants, parsed_data)** - Функция для преобразования данных в XML.

<h2>Примеры использования</h2>

Далее на рисунках представлены примеры описания конфигураций из разных предметных областей.

Настройки сервера

![1](https://github.com/user-attachments/assets/f98a2934-189a-4fd7-8e7b-74ebd9eb6a3a)

![2](https://github.com/user-attachments/assets/c5ea5932-ee46-4479-b4bb-005034c11922)

Настройки приложения

![3](https://github.com/user-attachments/assets/e19eca59-1236-4498-9273-4b2655716a9f)

![4](https://github.com/user-attachments/assets/248081b1-04cd-48d1-89af-bba005938fa0)

Настройки игры

![5](https://github.com/user-attachments/assets/68432373-9992-4158-b1b9-58b49326c1d4)

![6](https://github.com/user-attachments/assets/b6bc4a6f-0bc3-4596-9148-c6e35274ce6f)

<h2>Результаты прогона тестов</h2>

Все тесты были успешно пройдены

![7](https://github.com/user-attachments/assets/398a02bc-6e05-4b7e-8999-3119db6dbb02)
