# Решение задачи по прямоугольникам на плоскости

## Описание задачи

Даны прямоугольники на плоскости с углами в целочисленных координатах ([1..109],[1..109]). Требуется как можно быстрее выдавать ответ на вопрос «Скольким прямоугольникам принадлежит точка (x,y)?» И подготовка данных должна занимать мало времени. Уточнение: только нижние границы включены => (x1 <= x) && (x < x2) && (y1 <= y) && (y < y2).

## Решения

### 1. first_way

Простой алгоритм перебора. Прост в реализации, но может быть неэффективным при обработке большого количества прямоугольников.

### 2. second_way

Алгоритм на карте, использующий, вероятно, какую-то структуру данных для эффективного поиска прямоугольников, содержащих данную точку.

### 3. third_way

Алгоритм с использованием персистентного дерева отрезков, что позволяет быстро отвечать на запросы о принадлежности точек прямоугольникам.
