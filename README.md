|Прозвішча                      |  ДЗ1| ДЗ3 | ДЗ4 | ДЗ5 | ДЗ6 |iтог  |
|:------------------------------|:---:|----:|:---:|----:|:---:|----:|
|Асонов Дмитрий Геннадьевич     |  0  |     |     |     |     |     |
|Богданович Вероника Викторовна |     |     |     |     |     |     |
|Давыденко Александра Викторовна|  -5 |     |     |     |     |     |
|Демянович Владислав Павлович   |     |     |     |     |     |     |
|Киселев Артем Рональдович      |  2  |     |     |     |     |     |
|Линник Дмитрий Васильевич      |  0  |     |     |     |     |     |
|Савко Тимур Леонидович         |     |     |     |     |     |     |
|Станкевич Александр Олегович   |  7  |     |     |     |     |     |
|Семенович Роман                |  7  |
|Утлик Павел Дмитриевич         |  0  |     |     |     |     |     |
|Федосов Андрей Игоревич        |     |     |     |     |     |     |
|Шавеко Иван Геннадьевич        |     |     |     |     |     |     |
|Шишкарёв Иван Анатольевич      |     |     |     |     |     |     |


#Обязательные требования ко всем лабам:

• Текст задания, которое выполняется надо продублировать в первых строках решения как комментарий также надо вывод условия задачи как один из пунктов в меню (если создание меню есть в условии задачи)

• в main() только объявления переменных и вызовы функций. Вся реализация функций ОТДЕЛЬНО.
_________________________________
###Дополнительные плюсы  студентам, выжившим после капустника 13/10:

_Асомов,Богданович,Демянович,Киселев,Круковский,Савко,Семенеович_
_________________________________
##Задание на 28/10/2016 

`(в СВОЙ РЕПОЗИТОРИЙ записать файлы в кодировке UNICODE с именами     
2-1.cpp (тут решение 1-й задачи), 2-2.cpp (тут решение второй задачи)...`

1) Массив целых чисел размера N проинициализировать случайными числами из промежутка от 1 до N. "Перевернуть" массив (последний элемент станет первым, 1-й станет последним, 2-й поменяется с предпоследним и т.д.) **Внимательно проверьте случай нечетного N**

2) Массив целых чисел размера N проинициализировать случайными числами из промежутка от -N до N. Циклически сдвинуть элементы массива вправо на 1 элемент (последний элемент станет первым, 1-й станет 2-м, 2-й станет 3-м и т.д.) потом циклически сдвинуть элементы массива влево на 1 элемент (первый элемент станет последним, 2-й станет 1-м и т.д) 

3) Массив А целых чисел размера N проинициализировать случайными числами из промежутка от -N до N. **Не используя функции из задачи 2-2** Написать функции циклического сдвинга элементы массива вправо на k элементов (1-й станет 1+k -ым, 2-й станет 2+k -ым и т.д.) и влево на k элементов. В main написать вызов этих функций для числа k, которое вводит пользователь.
_Желательно придумать формулу вычисления нового индекса элемента чтобы обойтись одним циклом по
массиву А._

4) Массив целых чисел размера N проинициализировать случайными числами из промежутка от 1 до N. "Перетусовать" элементы массива двумя способами, предложенными на паре: с использованием доп.массива и просто меняя местами случайные элементы

---------------------
##Задание на 26/10/2016 

`(в СВОЙ РЕПОЗИТОРИЙ записать 5 или 6 файлов с именами     
1-1.cpp (тут решение 1-й задачи), 1-2.cpp (тут решение второй задачи), 1-3.cpp, 1-4.cpp, 1-5.cpp, 1-6.cpp)`

0) Пройти на http://euniversity.bsu.by входной тест Галкина.

1) Пользователь вводит с клавиатуры натуральное число, проверить корректность ввода, вычислить и вывести на экран сумму цифр введённого пользователем числа.

2)* Пользователь вводит с клавиатуры пятизначное натуральное число, которое сохраняется в переменную n, проверить корректность ввода, составить и вывести на экран число из цифр введённого числа n, так, чтобы выведенное число оказалось максимальным из возможных. Например, если пользователь ввёл число 22195, то программа должна вывести число 95221.

3) Пользователь вводит с клавиатуры натуральное число не большее 100, которое сохраняется в переменную n, проверить корректность ввода, создать массив из 10 случайных целых чисел из отрезка [-2n;n], вывести массив на экран в строку, подсчитать и и вывести на экран количество положительных чётных чисел в массиве.

4) Объявить массив вещественных чисел размера N (число N объявить как константу). Проинициализировать значения элементов массива случайными числами из промежутка от -50 до 50. 

Вывести значения сначала элементов с нечетными коэффициентами (1-й, 3-й, 5-й,...) а затем - с четными.

5) Объявить массив А вещественных чисел размера N (число N объявить как константу). Проинициализировать значения элементов массива случайными числами из промежутка от -50 до 50.

"Разделить" массив А на два массива: положительные записать в массив В, отрицательные - в С.

6)**_для желающих_  Объявить массив А вещественных чисел размера N (число N объявить как
константу).Проинициализировать значения элементов массива случайными числами из промежутка
от -50 до 50.

"Отсортировать" массив А на месте (т.е. не используя вспомогательных массивов В
и С) таким образом:положительные значения массива А переместить в начало, отрицательные переместить
в конец массива А.

(Проверить потом, что программа работает когда все элементы одного знака!)
