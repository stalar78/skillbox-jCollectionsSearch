# skillbox-CollectionsSearch

Цель задания
Научиться сортировать и искать элементы в коллекциях.

Что нужно сделать 

Реализуйте метод генерации «красивых» автомобильных номеров generateCoolNumbers() в классе CoolNumbers. Используйте следующие правила генерации номеров:
XYZ — различный набор из списка разрешенных букв, N — цифры, R — регион (от 01 до 199);
XNNNYZR — пример: A111BC197, У777HC66.
В госномерах автомобилей в РФ используются следующие буквы: А, В, Е, К, М, Н, О, Р, С, Т, У, Х.
В коллекции должно быть не менее 2 млн номеров.
Реализуйте методы поиска класса CoolNumbers по поиску номеров в каждой коллекции:
прямым перебором по ArrayList,
бинарным поиском по сортированному ArrayList,
поиском в HashSet,
поиском в TreeSet.
Измерьте и выведите длительность каждого метода поиска. Формат вывода результатов поиска:
Поиск перебором: номер найден/не найден, поиск занял 34нс
Бинарный поиск: номер найден/не найден, поиск занял 34нс
Поиск в HashSet: номер найден/не найден, поиск занял 34нс
Поиск в TreeSet: номер найден/не найден, поиск занял 34нс
 

Рекомендации
сортировка не входит в учёт времени для бинарного поиска;
для детального сравнения методов поиска используйте время в наносекундах:   System.nanoTime()
