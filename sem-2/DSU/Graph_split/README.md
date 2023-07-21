Дан неориентированный граф. Над ним в заданном порядке производят операции следующих двух типов:
- cut — разрезать граф, то есть удалить из него ребро;
- ask — проверить, лежат ли две вершины графа в одной компоненте связности.
  Известно, что после выполнения всех операций типа cut рёбер в графе не осталось. Найдите результат выполнения каждой из операций типа ask.
  Формат ввода

Первая строка входного файла содержит три целых числа, разделённые пробелами — количество вершин графа n, количество рёбер m и количество операций k (1 <= n <= 50000, 0 <= m <= 100000, m <= k <= 150000).
Следующие m строк задают рёбра графа; i-ая из этих строк содержит два числа ui и vi (1 <= ui,vi <= n), разделённые пробелами — номера концов i-го ребра. Вершины нумеруются с единицы; граф не содержит петель и кратных рёбер.
Далее следуют k строк, описывающих операции. Операция типа cut задаётся строкой „cut u v“ (1 <= u, v <= n ), которая означает, что из графа удаляют ребро между вершинами u и v. Операция типа ask задаётся строкой „ask u v“ (1 <= u, v <= n ), которая означает, что необходимо узнать, лежат ли в данный момент вершины u и v в одной компоненте связности. Гарантируется, что каждое ребро графа встретится в операциях типа cut ровно один раз.
Формат вывода

Для каждой операции ask во входном файле выведите на отдельной строке слово „YES“, если две указанные вершины лежат в одной компоненте связности, и „NO“ в противном случае. Порядок ответов должен соответствовать порядку операций ask во входном файле.