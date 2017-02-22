#Обязательные требования ко всем лабам:

• Текст задания, которое выполняется надо продублировать в первых строках решения как комментарий также надо вывод условия задачи как один из пунктов в меню (если создание меню есть в условии задачи)     
• в main() только объявления переменных и вызовы функций. Вся реализация функций ОТДЕЛЬНО.      
• имена переменных и функций должны соответствовать общепринятым нормам.

## Задание на 23.02
![Смотри картинку...] (https://github.com/BSU2016gr09/_Workflow/blob/master/joke.jpg)      

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

----------------------------------

|Прозвішча                      |  ДЗ1|ДЗ2-3| ДЗ4 | КР  |Диктант| ДЗ7 |iтог |комментарии |
|:------------------------------|:---:|----:|:---:|----:|:-----:|----:|----:|-----------:|
|Асонов Дмитрий Геннадьевич     |     |     |     |     |       |     |  5+ | 
|Богданович Вероника Викторовна |     |     |     |     |       |     |  6  | |
|Давыденко Александра Викторовна|     |     |     |     |       |     |  4  |
|Демянович Владислав Павлович   |     |     |     |     |       |     |  8|
|Киселев Артем Рональдович      |     |     |     |     |       |     |  5  |
|Круковский Сергей              |     |     |     |     |       |     |  5  ||
|Линник Дмитрий Васильевич      |     |     |     |     |       |     |  7+ |
|Савко Тимур Леонидович         |     |     |     |     |       |     |  6  |
|Станкевич Александр Олегович   |     |     |     |     |       |     |  5  |
|Семенович Роман                |     |     |     |     |       |     |  7.5|
|Утлик Павел Дмитриевич         |     |     |     |     |       |     |  5  |
|Федосов Андрей Игоревич        |     |     |     |     |       |     |  7  | |
|Шавеко Иван Геннадьевич        |     |     |     |     |       |     |  7  | |
|Шишкарёв Иван Анатольевич      |     |     |     |     |       |     | 7.51|

----------------------------------
