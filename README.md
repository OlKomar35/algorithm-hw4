Необходимо доработать структуру класса HashMap, реализованную на семинаре.

У нас появился метод добавления элементов, каким образом я могу распечатать все элементы структуры хэш-таблицы на экране?

1. Задача: Распечатайте все элементы структуры HashMap переопределив метод toString() - самый простой вариант.
2. (Дополнительная, необязательная задача) Добавить возможность перебора всех элементов нашей структуры данных, необходимо
добавить несколько элементов, а затем перебрать все элементы структуры HashTable используя цикл foreach. Подумайте, 
возможно вам стоит обратиться к интерфейсу Iterable и в рамках имплементации подобного интерфейса создать объект типа
Iterator, далее, вы реализуете метод next и hasNext, наделите способностью нашу структуру HashMap быть перечисляемой.