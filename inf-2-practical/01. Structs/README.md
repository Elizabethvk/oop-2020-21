# Структури

## Задача 1
1. Дефинирайте структура Book, която се характеризира със заглавие, автор - низове с дължина до 
256 символа, и ISBN номер - низ с дължина 13 символа.
2. Да се реализират следните функции:
- `add_book`: приема указател към края на масив от книги и добавя книга към края му
- `remove_book`: приема указател към началото и края на масив от книги и премахва книга от него по ISBN номер (ISBN номерата са уникални за всяка книга)
- `print_books`: приема указател към началото и края на масив от книги и извежда всички книги от него на стандартния изход

## Задача 2
1. Дефинирайте структура ComplexNumber, която представя комплексно число в алгебричен вид.
2. Реализирайте функции, които събират и умножават 2 комплекни числа.
3. Напишете функция, който да извежда комлексно число по подходящ начин на стандартния изход. 

## Задача 3
1. Дефинирайте структура Point, която представя точка в двуизмерно пространство. Координатите на точките са цели числа в интервала [1; 100].
2. Реализирайте функция, която по подадени 4 точки A, B, C и D да определя дали фигурата ABCD е правоъгълник. За целите на задачата считаме, че правоъгълник е четириъгълник, чиито страни са успоредни на координатните оси. 
3. Реализирайте функция, която по подадени 4 точки A, B, C и D да намира лицето на ABCD, ако е правоъгълник. Помислете как бихте се справили със случая, в който подадените точки не образуват правоъгълник. 