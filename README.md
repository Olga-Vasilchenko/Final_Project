# Описание итоговой проверочной работы
*Решение задачи:*

Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа.
Первоначальный массив можно ввести с клавиатуры, 
либо задать на старте выполнения алгоритма.

## Последовательность выполнения действий:

- объявляем два массива array1 и array2;
- объявляем счетчик count, который будет считать элементы
из первого массива, которые будут соответствовать условию выборки, 
то есть <= 3 и заносить во второй массив;
- проверяем каждое значение массива на соответствие условию;
- если строка соответствует условию, кладем в новый массив, 
если не соответствует, то позвращаемся к условию;
- проходим по заданному циклу, пока не закончится массив;
- все элементы, соответствующие условию кладем в новый массив и выводим на печать.

Блок-схема
![Sxema](Sxema.png)
![Sxema](file:///D:/Downloads/Схема.drawio.html)

После написания блок-схемы пишем программу, решающую задачу через метод Void.