# GoodCode
4.4 ДЗ по теме "Свойства хорошего кода и принцип SOLID"

1 Магические числа
Убрал число 4 из поля purchases класса Purchase, для этого переменную products из класса main перенес в статическое поле класса Main, размер массива purchases исправил с 4 на Main.products.size()

2 Dependency inversion principle (SOLID)
Вместо HashMap<String, Integer> products инициализировал Map<String, Integer> products

3 KISS (подсказала идея)
В методе sum класса Purchase исправил цикл for на foreach - читабельность кода улучшилась

4 Cleanup код (тоже подсказала идея)
Перекастовал в методе sum класса Purchase правую часть выражения sum += -> в тип long
