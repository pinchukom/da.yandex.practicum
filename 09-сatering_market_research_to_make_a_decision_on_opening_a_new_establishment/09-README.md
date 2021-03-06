# Исследование рынка общественного питания г.Москвы

## Цель
Принять решение об открытии нового кафе с инновационной идеей на основе открытых данные о заведениях общественного питания в Москве

## Задача
Исследование рынка общественного питания на основе открытых данных, подготовка презентации для инвесторов

## Описание
Датасет содержит следующие данные:
- идентификатор объекта;
- название объекта общественного питания;
- сетевой ресторан;
- тип объекта общественного питания;
- адрес;
- количество посадочных мест.

## Сфера деятельности
Бизнес, Оффлайн, Стартапы


## Вывод
1. В общем распространении преобладает формат кафе, далее, с отрывом почти в 2 раза, идут столовые и рестораны
2. Кол-во не сетевых заведений больше в 4 раза
3. Сетевое распространение преобладает среди предприятия быстрого питания, кафе, рестораны, но даже в этих категориях большую долю занимают не сетевые рестораны
4. Среди сетевых заведений нет определенной корреляции между кол-вом заведений и посадочных мест в них
5. В среднем больше всего посадочных мест в столовых(130 мест) и ресторанах (96 мест)
6. Больше всего заведений сосредоточено в Зеленограде- отделенный округ г. Москвы, в основном изолирован от остальной Москвы, но является центром для окружающих его районов Подмосковья. Далее идет пр. Мира (несколько районов)- здесь сосредоточены ВДНХ, гостиница Космос, Рижский вокзал- одни из значимых туристических объектов г. Москвы.
7. Больше всего улиц с 1 заведением сосредоточены в районе Марьина Роща, их там 16шт.В данном районе расположены Савеловский рынок (самый крупный ИТ рынок) и рижский вокзал. Эти крупные объекты являются точками притяжения и работы иммигрантов среди которых популярны небольшие и не дорогие заведения.
8. Распределение кол-ва посадочных мест по улицам прямо связано с кол-во заведений на ней, чем больше заведений, тем больше посадочных мест. Корреляция между этими параметрами очень высокая (0,93)

## [Презентация](Public_ catering_market_research.pdf) 

## Используемые библиотеки
- pandas
- numpy
- plotly
- requests
- json
- io 

## Статус проекта
Завершен
