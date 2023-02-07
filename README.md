# CastCalculation

## Вычисление стоимости товара

## Постановка задачи
Напишите программу, которая вычисляет полную стоимость товара. Данные, используемые для расчета: стоимость единицы товара в рублях, количество единиц товара, 
включение/не включение НДС (20%) в стоимость товара. Если количество единиц товара больше или равно 10, то действует скидка 5%.

Подсказка: для получения полной стоимости товара используйте перегруженные методы.

1. Реализуем метод получения полной стоимости товара без включения НДС и без скидки.
1. Для получения стоимости товара без включения НДС, но с учетом скидки, воспользуемся перегрузкой метода и создадим метод с таким же именем, 
где дополнительно в параметры добавим скидку.
Результат расчета метода округлим до копеек.
1. Еще раз воспользуемся перегрузкой метода для расчета стоимости товара, включая НДС, но без скидки.
1. И еще раз перегрузим метод для расчета стоимости товара, включая НДС и со скидкой.

Получим четыре метода с одинаковым именем, но с разным набором параметров.

Вставим в четыре ветки нашего цикла расчета стоимости необходимый перегруженный метод.
