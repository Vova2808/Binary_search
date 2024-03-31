# Бинарный поиск на Python

<strong>Двоичный, или бинарный, поиск значения</strong> в списке или массиве используется только для упорядоченных последовательностей, то есть отсортированных по возрастанию или убыванию. Заключается в определении, содержит ли массив искомое значение, а также в определение места его нахождения.

<br>


### Описание алгоритма

- 1. Находится средний элемент последовательности. Для этого первый и последний индексы связываются с переменными, а индекс среднего элемента вычисляется.
- 2. Значение среднего элемента сравнивается с искомым значением. Если значение среднего элемента оказывается равным искомому, поиск завершается.
- 3. Иначе, в зависимости от того, искомое значение больше или меньше значения среднего элемента, дальнейший поиск будет происходить только в левой или только в правой половинах массива.
- 4. Для этого одна из границ исследуемой последовательности сдвигается. Если искомое значение больше значения среднего элемента, то нижняя граница сдвигается за средний элемент на один элемент справа. Если искомое значение меньше значения среднего элемента, то верхняя граница сдвигается на элемент перед средним.
- 5. Снова находится средний элемент теперь уже в выбранной половине. Описанный выше алгоритм повторяется для данного среза.