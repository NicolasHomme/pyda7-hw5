
Лекция 5. Регулярные выражения и основы синтаксического разбора 
Репозиторий для домашего задания по лекции

Домашнее задание к лекции "Регулярные выражения"

Для зачета необходимо выполнить 4 задания.
Для зачета с отличием – все.
Задание 1

Напишите функцию, которая принимает на вход строку и проверяет является ли она валидным транспортным номером. Если да, то функция должна возвращать отдельно номер и регион.

​

Задание 2

Напишите функцию, которая проверяет e-mail адрес на валидность по стандарту RFC822: http://www.w3.org/Protocols/rfc822/. Для этого постарайтесь написать (в крайнем случае найти) самый полный шаблон для проверки e-mail адресов через регулярное выражение. Разберитесь и напишите примеры, какие ваш шаблон может не охватить.

​

Задание 3

Напишите функцию, которая будет удалять все последовательные повторы слов из заданной строки.

​

Задание 4

Напишите функцию, которая будет проверять номер сотового телефона на валидность, если он валиден, то переводить его в формат:
+7(xxx)-xxx-xx-xx
Постарайтесь предусмотреть как можно больше адекватных форматов изначального ввода номера. Примеры правильных и неправильных форматов:

    +7 955 555-55-55;
    955555555;
    8(955)555-55-55;
    +7 955 555 55 55;
    7(955) 555-55-55;
    +7 955+555+55+55.

