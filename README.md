Задача: Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

Блок схема  https://github.com/RUStAMERQ/qwerty/blob/0f68b364eeb63ddc26569368dd78e3a137672e04/diagram%20(1).png

Код  https://github.com/RUStAMERQ/qwerty/blob/92b202ffe847609479287ddc0a623cca942c726a/%D0%9A%D0%BE%D0%B4

Решение:

1.Обьявлено два массива.

2.Применяем метод void,используем цикл for, в котором проверяем соответствие длинне массива.
Внутри цикла проверяем условие меньше или равно 3 символам,если да ,то элемент первого массива заносится в count элемента второго массива.После присвоения увеличивается переменная count на 1 и возвращается к циклу for в котором Q увеличивается на 1.

3.Печать массива.
