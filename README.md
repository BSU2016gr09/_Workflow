
----------------------------------

|Прозвішча                      |ДЗ1-3| ДЗ4| КР1 |KP2 | ДЗ7 |Семестр1 |
|:------------------------------|:--:|:---:|----:|:---:|----:|----:|
|Асонов Дмитрий Геннадьевич     |    |     |     | 4   |     |  7 | 
|Богданович Вероника Викторовна |    |     |     | 8   |     | 7  |
|Давыденко Александра Викторовна|    |     |     | 2   |     | 5  |
|Демянович Владислав Павлович   |    |     |     |  8  |     | 9  |
|Киселев Артем Рональдович      |    |     |     | 2   |     | 6  |
|Линник Дмитрий Васильевич      |    |     |     | 5   |     | 8  |
|Савко Тимур Леонидович         |    |     |     |     |     | 6  |
|Станкевич Александр Олегович   |    |     |     | 7   |     | 7  |
|Семенович Роман                |    |     |     |     |     | 8  |
|Утлик Павел Дмитриевич         |    |     |     |     |     | 5  |
|Федосов Андрей Игоревич        |    |     |     | 7   |     | 9  |
|Шавеко Иван Геннадьевич        |    |     |     | 4   |     | 9  |
|Шишкарёв Иван Анатольевич      |    |     |     |     |     | 9  |

----------------------------------


# Обязательные требования ко всем лабам:

• Текст задания, которое выполняется надо продублировать в первых строках решения как комментарий       
также стоит реализовать вывод условия задачи как один из пунктов в меню (если создание меню есть в условии задачи)     
• в main() только объявления переменных и вызовы функций. Вся реализация функций ОТДЕЛЬНО.      
• имена переменных и функций должны соответствовать общепринятым нормам.

## Задание на 27.04 Объекты, структуры

Скачать себе образцы решенных задач с \\mmf-fs\Faculty\Дневное отделение\Кафедра Web-технологий\1_Kurs\Практика по C++ (Барвенов)

## Задание на 13.04 Объекты, структур

0) Готовимся наконец то программировать классы в которых есть "динамические" массивы или в которых хранятся указатели. Чтобы еще раз понять зачем нам приходится в этом случае писать самостоятельно The Great 3(5) читаем внимательно http://lektsia.com/1x33a8.html и самый конец предыдущей страницы на том сайте!!! 

## Задание на 13.04 Объекты, структуры
0) Обещанная ссылка на реализацию класса студент: http://blog.kislenko.net/show.php?id=1465

Лекции с подробными объяснениями лабораторных http://ermak.cs.nstu.ru/cprog/HTML/index.htm

1) Летом читать и выполнять!!! Сейчас - просто читать книгу: Лаптев В.В. C++. Объектно-ориентированное программирование  

2) Доделать (учитывая мои комментарии в ваших репозиториях) свои проекты с дополнительной реализацией конструкторов, деструкторов (в которых, просто выдается сообщение, что он сработал) и операций =, +,- тех простейших классов, которые вы делали к 6.04     
**В main() надо не только объявить 2-3 объекта вашего класса, но и сделать пару-тройку указателей на объеты!!! Проинициализировать некоторые из них теми объетами, которые уже есть, а некоторые проинициализировать с помощью оператора,  NEW**. После этого, в main выполнить пару-тройку действий с объектами и с указателями (присвоение, сумма, удаление...) чтобы показать, что все методы работают! 

## Задание на 30.03 СТРОКИ,Файлы И УКАЗАТЕЛИ
1) Напоминаю. что желающие могут сдать программу генерирующее начальное состояние для игры в 15.     
Желающие могут сдать программу для анализа файлов bmp.

2) Выбрать ОДНО задание из списка ниже и разработать программу, предусмотрев в ней:     
•	последовательное чтение строк **из входного текстового файла** (ПОСТРОЧНОЕ, а не весь файл целиком или побайтово);    
### Программа тестируется на текстовом файле "Война и мир" (100500строк) ###     
•	использование указателей при работе со строками;     
•	использование библиотечных функций <cstring> для работы со строками (т.е. нельзя в программе обратиться к символам строки как str[1] или str[i]);     
•	создание нескольких собственных функций для обработки строк;     
•	вывод результатов **в новый текстовый файл (result.txt)**;     
•	поощряется использование меню на массиве указателей на функции.

**Попроще итоговая оценка меньше 8**    
•	(Богданович) Определить, сколько раз стоящие рядом два слова в тексте начинаются на одну и ту же букву. Вывести эти слова.     
•	(Давыденко) Найти и вывести все слова в тексте, в которых первый и последний символы совпадают.     
•	Найти и вывести все слова в тексте, в которых первый и последний символы совпадают и длина которых чётная. Удалить все такие слова.     
•	В тексте найти и вывести слова, длина которых - простое число. Вставить после первого слова, длина которого простое число, заданную подстроку (которую вводит изначально пользователь).     
•	В тексте найти и вывести на экран все слова-анаграммы (читаются одинаково слева направо и справа налево).     
•	(Шавеко) В тексте удалить все слова, содержащие заданную букву ровно два раза.     
•	(Станкевич) После каждого слова в тексте, оканчивающегося заданной подстрокой, вставить указанный символ.     
•	Заменить все слова в тексте заданной подстрокой (которую вводит изначально пользователь), если длина слова совпадает с длиной подстроки и слово содержит хотя бы одну цифру.     
•	Найти и вывести все слова текста, в которых все буквы различны.     
•	(Линник) Определить, сколько слов в тексте имеют заданную длину k. Вывести такие слова.     
•	Определить, сколько слов в тексте имеют одинаковую длину. Вывести все слова длины k.     
•	(Асонов) В каждой строке текста удалить фрагменты, заключённые в круглые скобки.     
•	(Киселев)В строках текста удалить фрагменты, заключённые в круглые скобки.     
•	В тексте найти сумму цифр, содержащихся во всех словах и слово с максимальной суммой цифр.     

**Посложнее**  
•	В тексте удалить фрагменты, заключённые в круглые скобки (скобка может начинаться в одной строке, а заканчиваться -  другой. Могут быть вложенные скобки, но они всегда верно расставлены. Т.е. нет ситуации "(...(...)..()" ).     
•	(Демянович)Определить есть ли в тексте слово, которое встречается ровно k раз, удалить все такие слова кроме последнего.     
•	В тексте найти и вывести все слова максимальной длины, и удалить за ними следующее слово.В тексте поменять местами слова минимальной и максимальной длины (если таких слов несколько, то брать первое).  

**Серъезное**  
(Федосов) В тексте определить частоту вхождения слов. Вывести "словарь" текста (не обязательно в алфавитном порядке).

## Задание на 10.03

0) Доделать и залить в репозиторий программы, которые должны были сделать к прошлому занятию!  
1) Готовимся программировать динамические структуры данных (стек, дек, очередь). Читаем теорию http://learnc.info/adt/

2) Выбираем одну задачу по работе с массивами из списка и реализуем её.       
**Попроще**       
• (Давыденко) В массиве А(N,М) найти номер строки, среднее арифметическое положительных элементов которой является наименьшим и поменять её с первой строкой.    
• (Станкевич) В массиве А(N,N) найти первую строку, не содержащую отрицательных элементов, и поменять её с последней строкой.       
• В массиве А(N,М) найти строку, для которой количество перемен знаков максимально и поменять её с первой строкой.        
• В массиве А(N,N) найти максимальные элементы нижнего и верхнего треугольников относительно главной диагонали и поменять местами строки в которых они находятся.       
•	(Линник) В массиве А(N,М) поменять местами строки, содержащие максимальный и минимальный элементы.        
•	(Шавеко) В массиве А(N,М) часть строк состоит из нулей. удалить нулевые строки.       
•	В массиве А(N,М) сменить знаки минимальных элементов и удалить строку с минимальным произведением элементов.       
•	(Богданович) В массиве А(N,М) расположить строки в порядке возрастания их максимальных элементов.        
•	В массиве А(N,М) расположить строки в порядке возрастания количества минимальных элементов в каждой строке.    
•	(Асонов) В массиве А(N,M) переставить строки в порядке возрастания элементов последнего столбца.     
•	В массиве А(N,M) переставить строки так, чтобы строка с максимальной суммой элементов стала первой строкой, а остальные строки расположить в порядке возрастания элементов первого столбца.     

**Посложнее немножко**       
• В массиве А(N,M) расположить строки, стоящие после строки с первым максимальным элементом матрицы, в порядке возрастания количества чётных элементов в строке.      
• (Указатели на столбцы.) В массиве А(N,M) переставить столбцы так, чтобы столбец с максимальной суммой элементов стал первым, а остальные столбцы расположить в порядке возрастания элементов первой строки.        
• (Указатели на столбцы.)	В массиве А(N,M) расположить столбцы по возрастанию количества чётных элементов в столбце.        
• (Семенович)	В массиве А(N,M) расположить столбцы по возрастанию значений минимальных элементов столбцов.        
• (Указатели на столбцы.) В массиве А(N,M) элементы столбцов, не содержащих нулевых элементов, расположить в порядке убывания, а сами столбцы расположить в порядке возрастания элементов первой строки.        
• (Указатели на столбцы.)	В массиве А(N,M) расположить элементы каждого столбца в порядке возрастания модулей их отрицательных элементов, а сами столбцы расположить в порядке убывания  сумм их элементов.        
• (Указатели на столбцы.)	В массиве А(N,M) расположить положительные элементы каждого столбца в порядке возрастания, а сами столбцы расположить в порядке убывания их первых максимальных элементов.        
• (Указатели на столбцы.)	В массиве А(N,M) расположить в порядке возрастания элементы столбцов, максимальный элемент которых не превосходит заданную величину р, а сами столбцы расположить в порядке возрастания количества нечётных элементов в столбце.        
• (Указатели на столбцы.)	В массиве А(N,M) расположить в порядке возрастания элементы столбцов, максимальный элемент которых не превосходит заданную величину р, а сами столбцы расположить в порядке возрастания количества перемен знаков в каждом столбце.        
• (Шишкарев)	В массиве А(N,M) расположить столбцы в порядке  возрастания количества нулевых элементов в каждом столбце.       
• (Киселев)	В массиве А(N,М) удалить столбцы, все элементы которых являются простыми числами.       
• (Савко)	В массиве А(N,М) столбец с минимальным количеством нечетных элементов поменять местами с последним столбцом.       
• (Демянович)	В каждом столбце массива А(N,М) после первого отрицательного элемента вставить максимальную цепочку из положительных элементов данного столбца. Расположить столбцы в порядке возрастания по количеству вставленных элементов. 

## Задание на 3.03
![Посмотреть видео...] https://www.youtube.com/watch?v=SyWFvn0I6m8

Подумать, не докладываешь ли ты свои результаты так-же!!!    
0) Доделать и залить в репозиторий программы, которые должны были сделать к прошлому занятию!   
1) Линейный конгруэнтный генератор псевдослучайных чисел  
Для большинства программ использующих случайность достаточно не настоящих случайных чисел, а лишь чисел, которые ведут себя похожим образом. Поэтому на практике находят очень широкое применение алгоритмы генерации псевдослучайных чисел. Простейшим и обычно самым быстрым из них является *линейный конгруэнтный метод*.  
Суть метода выражается в нахождение следующего псевдослучайного числа по предыдущему по представленной формуле:  

x(n+1) = (a*x(n) + c) mod m;

где x(n+1) новое псевдослучайное число, x(n) — старое, mod это сравнимость по модулю, что практически полностью соответствует нахождению остатка при делении на m,  
1 <= a < m, 0 < c < m 
и m некоторые коэффициенты, которые и определяют последовательность псевдослучайных чисел.  
Не каждый набор коэффициентов определяет последовательность похожую на случайные числа, так например a = 7 c = 8 m = 16, порождают последовательность чередующихся 0 и 8.  
Для хорошей генерации должны быть выполнены следующие правила:  
1. Числа c и m взаимно простые;  
2. a - 1 кратно p для каждого простого p, являющегося делителем m;  
3. a - 1 кратно 4, если m кратно 4.  
Реализовать линейный конгруэнтный генератор псевдослучайных чисел.  
(a) Используя коэффициенты из википедии, например a=4096, c=150889, m=714025.  
(b) Подобрав собственные коэффициенты по правилам, не использую готовые коэффициенты из википедии.  

2) В 2003 году Джордж Марсаглия предложил быстрый алгоритм XORShift генерации псевдослучайных  чисел с использованием XOR (в С++ эта операция обозначается через знак ^ ) и битовыми сдвигами. Алгоритм состоит из 3 действий:

tmp = XOR(x(n),x(n)<<a) ;

tmp = XOR(tmp,tmp>>b) ;

x(n+1) = XOR(tmp,tmp<<c) ;

Начальное значение x(0) можно выбирать любое. Начиная с него и начнется генерация чисел (аналогично srand(____) для начала работы с rand()). “Магические“ числа а,b и с подбираются самостоятельно. 
В частности, при 21, 35 и 4 генерируют последовательность с полным периодом равным 2^64-1.

Можно использовать числа 13,15,5.

Реализуйте этот алгоритм в качестве отдельной функции, чтобы потом выполнять задания на массивы (там где надо случайными числами заполнить массив)!

## Задание на 23.02
`Разработать программу для работы с одним или несколькими динамическими одномерными массивами, предусмотрев в ней:`

•	Размер массива N запрашивать у пользователя;      
•	выделение и контроль динамической памяти **в отдельной функции**, а не в main;      
•	организация циклов **с использованием указателей**, а не с помощью A[i];     
•	функции для инициализации, для ввода, для вывода массивов в heap;      
•	удаление динамической памяти после её использования;      
•	в зависимости от варианта задания одну или несколько функций для обработки массивов (для сортировки новый массив не создавать);     

1. Расположить в порядке возрастания элементы массива А(N), начиная с k-го элемента.
2. Даны точки плоскости своими координатами в виде двух одномерных массивов. Точки плоскости рассортировать по возрастанию расстояния до прямой ax + by + c = 0.
3. Положительные элементы массива А(N) переставить в конец массива, сохраняя порядок следования. Отрицательные элементы расположить в порядке убывания. Дополнительный массив не использовать.
4. Элементы массива А(N), значения которых – простые числа, расположить в порядке возрастания, не нарушая порядка следования других элементов.
5. Подготовить для работы в аудитории функции для выделения памяти для **двумерного массива**, функции для инициализации...      
**Прототипы функций:**     

* void give_memory(int**&, int, int)//первый способ. Подумайте, почему обязательно надо тут &
* int** give_memory(int, int)//второй способ
* void init_array(int **,int,int)
* void print_array(int **,int,int)
* void free_array(int **,int,int)

## задание на 16.02

Прочитать, скачать себе и ** распечатать ** хорошее краткое объяснение указателей с адреса http://www.math.spbu.ru/user/dlebedin/ncpp4.pdf
