# Что должна делать программа?
1. Рисовать примитивы, менять их расположение
2. Выделять и удалять нарисованные примитивы
3. Позволять задавать правила, которым должны удовлетворять объекты (причем только те, которые возможны для выбранного типа объектов)
4. Сохранять результаты работы в файлы с возможностью дальнейшей работы с ними


# Что есть

1. Точки   (Points)
2. Отрезки (Sections)
3. _Дуги    (Arcs)_

# Структура
  `main.cpp`
  
  `ReadMe.md`
  
  /`include`
  
  _`DynArray.h`
  
  _`LinkedList.h`
  
  _`Vector.h`
  
  /`src`
  
  _`DynArrayP.cpp`
  
  _`DynArrayS.cpp`
  
  _`LinkedList.cpp`
  
# Домашние задания

## 1. Продумать хранилище отрезков

   Написать такую же программу для отрезков:
   вводим с клавиатуры + определяем все отрезки, ортогональные друг другу.
   Найденные отрезки модифицируем так, чтобы они были параллельны друг другу (через вектора (х,у) и (-у,х)).
 
   Даны две точки и какое-то расстояние. Модифицировать эти точки так, чтобы расстояние между ними стало равным данному.

## 2. Дополнить программу
   1. Написать программу, позволяющую пользователю вводить информацию о точках и отрезках + проверяющую, принадлежат ли какие-либо введенные точки введенным отрезкам. " `%point_name%` принадлежит `%segment_name%` "
   2. Избавиться от `[]` в `Point &LinkedList::operator[] ()`
   3. В `LinkedList.h` дописать `Point & GetCurrent` *50 строка*
   4. *50 - 70 строки* реализовать для массива 
