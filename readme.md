## Задание
***
### Вариант 17
Описать обобщенный класс с именем ZNAK, содержащую следующие поля:
- Идентификационный номер
- Имя
- Фамилия
- Знак Зодиака
- Дата Рождения (массив из трех чисел)

Написать программу, выполняющую следующие действия:
- Ввод с клавиатуры данных в массив, состоящий из восьми элементов типа ZNAK (записи должны быть упорядочены по знакам Зодиака);
- Вывод на экран информации о людях, родившихся в месяц, значение которого введено с клавиатуры (если таких нет, вывести соответствующее сообщение).
- Реализовать интерфейс IClonable для клонирования объектов класса ZNAK. Реализовать интерфейс IComparable для реализации сортировки по полю Знак Зодиака. Создать класс, реализующий интерфейс IComparer для сортировки класса ZNAK по полю Дата рождения.