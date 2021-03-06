# A/B-тестирование

## Задача

Ваша задача — провести оценку результатов A/B-теста. В вашем распоряжении есть датасет с действиями пользователей, техническое задание и несколько вспомогательных датасетов.

- Оцените корректность проведения теста
- Проанализируйте результаты теста

Чтобы оценить корректность проведения теста, проверьте:

- пересечение тестовой аудитории с конкурирующим тестом,
- совпадение теста и маркетинговых событий, другие проблемы временных границ теста.


## Вывод

1. Конверсия из авторизации в заход на строницу продукта - 66%, cо страницы продукта в покупку конверсия 50%, из авторизации в покупку- 33%.
2. В группе A в среднем 6 событий на пользователя, а в группе В- 5 событий
3. С 13 по 21 декабря наблюдается рост по кол-ву событий и далее спад
4. В период проведения теста проводилось маркетинговое мероприятие 'christmas&new year promo' 
5. 887 пользователей из попавших в наш тест так же приняли участие в конкурируещем тесте 'interface_eu_test'
6. 52% новых пользователей в тесте из региона EU

**Различие конверсии по группам теста:**
- Конверсия в просмотр карточек товаров: Группа В показывает стабильно более низкие показатели, чем группа А
- Конверсия в просмотр корзины: 30 декабря группа В показывает значительный скачек в просмотре корзины, но так как нет данных по этому дню в группе А, сказать что-то определенное нельзя, возможно это нормальное поведение перед праздником. В первые 9 дней теста группа В соревновалась с группой А, но далее показывает более низкие значения конверсии
- Конверсии покупок: с 14 до 29 декабря группа В показывает стабильно более низкие значения в кол-ве покупок

Проверка статистической разницы долей z-критерием показала наличие разницы между долями

По данным конверсии группа В показывает более низкие значения, что говорит о том что тест прошел не успешно, но т.к. в период проведения теста проводилось 2 маркетинговых мероприятия и конкурирующий тест - нельзя определенно сказать, что полученные результаты являются следствием только внедрениея улучшенной рекомендательной системы.

Рекомендую в период проведения маркетинговых мероприятий не проводить тестирование нового функционала, для чистоты данных. Кроме того проведение теста в период маркетинговых мероприятий может негаливно сказаться на результаты маркетингового мероприятия, например сократить приток клиентов и снизить выручку.

## Используемые библиотеки
- pandas
- numpy
- datetime
- scipy
- plotly.graph_objects
- math
- warnings


## Статус проекта
Завершен

