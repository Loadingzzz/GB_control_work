# Контрольная работа

## Задача

Написать программу, которая из имеющегося массива строк формирует новый массив из строк, длина которых меньше, либо равна 3 символам. Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

## Решение

### Этапы решения данной задачи

1. Нарисуем блок-схему алгоритма
2. Напишем алгоритм на C#, исходя из блок схемы

### Описание работы алгоритма

Изначально задан массива строк (`stringArray`). Мы создаем пустой вспомогательный массив (`resultArray`), в который будем заносить строки размером меньше либо равные 3. Создаем функцию, в которой будет счетчик (`count`). Далее используя цикл For, мы проходимся по элементам изначального массива и задаем условие, если длинна элемента массива меньше либо равна 3, том этот элемент массива мы заносим в вспомогательный массив, счетчик увеличивается на 1 и мы продолжаем итерацию. Если условие не соблюдается то, счетчик увеличивается на 1 и мы продолжаем итерацию. Цикл будет идти до тех пор, пока мы не переберем все элементы изначального массива.
В результате мы получаем изначальный массив и воспомогательный массив, в котором будут содержаться элементы соответствующие условиям задачи.

Блок схема представлена по пути `sheme/control_work_sheme.drawio`

Алгоритм решения задачи представлен по файле `Program.cs`

Ссылка на [репозиторий](https://github.com/Loadingzzz/GB_control_work)
