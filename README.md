Задача :
Написать программу, которая из имеющегося массива строк формирует массив из строк, длина которых меньше либо равна 3 символа. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решение не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами  
Описание решения:  
Задаётся два массива , объявляется метод с циклом for ,внутри цикла проверяется условие на длину строк, если <=3, то элемент первого массива заносится в элемент второго, если нет, то count увеличивается на 1 и возвращается в for, где i увеличивается на 1. Цикл действует до тех пор пока не выйдет за длину массива. В конце выводятся строки либо равные 3 либо меньше 3 элементов.
![Image1](https://user-images.githubusercontent.com/112129683/195408773-2be398cc-19de-4baa-aece-338d5b6898cc.png)
