__Задание:__

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами

__Алгоритм решения:__

Сначала объявляем два массива: изначальный и второй такой же длинны. Потом объявляем метод, в котором цикл соразмерный длинне массива. Внутри цикла проверяем условие ( <=3 ). Если условие соответствует, то элемент первого массива заносится в count элемент второго массива. Переменная count, чтобы поочередно закидывать из первого массива во второй и чтобы потом не было пробелов. После присвоения переменная count увеличивается на 1 и возвращается к циклу for в котором i увеличивается на 1. И так проверяется до конца.
