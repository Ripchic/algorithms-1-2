Реализуйте структуру данных из
n
элементов
a
1
,
a
2
…
a
n
, поддерживающую следующие операции:
присвоить элементу
a
i
значение
j
;
найти знакочередующуюся сумму на отрезке от
l
до
r
включительно (
a
l
−
a
l
+
1
+
a
l
+
2
−
…
±
a
r
).
Формат ввода

В первой строке входного файла содержится натуральное число
n
(
1
≤
n
≤
1
0
5
) — длина массива. Во второй строке записаны начальные значения элементов (неотрицательные целые числа, не превосходящие
1
0
4
).
В третьей строке находится натуральное число
m
(
1
≤
m
≤
1
0
5
) — количество операций. В последующих
m
строках записаны операции:
операция первого типа задается тремя числами 0 i j (
1
≤
i
≤
n
,
1
≤
j
≤
1
0
4
).
операция второго типа задается тремя числами 1 l r (
1
≤
l
≤
r
≤
n
).
Формат вывода

Для каждой операции второго типа выведите на отдельной строке соответствующую знакочередующуюся сумму.