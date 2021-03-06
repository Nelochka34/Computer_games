## Описание проекта
Вы работаете в интернет-магазине «Стримчик», который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Вам нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.
Перед вами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и вы планируете кампанию на 2017-й. Нужно отработать принцип работы с данными. Неважно, прогнозируете ли вы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.
В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».
### Инструкция по выполнению проекта
- Шаг 1. Откройте файл с данными и изучите общую информацию </br>
- Шаг 2. Подготовьте данные </br>
        - Замените названия столбцов (приведите к нижнему регистру); </br>
        - Преобразуйте данные в нужные типы. Опишите, в каких столбцах заменили тип данных и почему; </br>
        - Обработайте пропуски при необходимости: </br>
        - Объясните, почему заполнили пропуски определённым образом или почему не стали это делать; </br>
        - Опишите причины, которые могли привести к пропускам; </br>
        - Обратите внимание на аббревиатуру 'tbd' в столбце с оценкой пользователей. Отдельно разберите это значение и опишите, как его обработать; </br>
        - Посчитайте суммарные продажи во всех регионах и запишите их в отдельный столбец. </br>
- Шаг 3. Проведите исследовательский анализ данных </br>
        - Посмотрите, сколько игр выпускалось в разные годы. Важны ли данные за все периоды? </br>
        - Посмотрите, как менялись продажи по платформам. Выберите платформы с наибольшими суммарными продажами и постройте распределение по годам. За какой характерный срок появляются новые и исчезают старые платформы? </br>
        - Возьмите данные за соответствующий актуальный период. Актуальный период определите самостоятельно в результате исследования предыдущих вопросов. Основной фактор — эти данные помогут построить прогноз на 2017 год. </br>
        - Не учитывайте в работе данные за предыдущие годы.</br>
        - Какие платформы лидируют по продажам, растут или падают? Выберите несколько потенциально прибыльных платформ. </br>
        - Постройте график «ящик с усами» по глобальным продажам игр в разбивке по платформам. Опишите результат. </br>
        - Посмотрите, как влияют на продажи внутри одной популярной платформы отзывы пользователей и критиков. Постройте диаграмму рассеяния и посчитайте корреляцию между отзывами и продажами. Сформулируйте выводы. </br>
        - Соотнесите выводы с продажами игр на других платформах. </br>
        - Посмотрите на общее распределение игр по жанрам. Что можно сказать о самых прибыльных жанрах? Выделяются ли жанры с высокими и низкими продажами? </br>
- Шаг 4. Составьте портрет пользователя каждого региона </br>
        - Определите для пользователя каждого региона (NA, EU, JP): </br>
        - Самые популярные платформы (топ-5). Опишите различия в долях продаж. </br>
        - Самые популярные жанры (топ-5). Поясните разницу. </br>
        - Влияет ли рейтинг ESRB на продажи в отдельном регионе? </br>
- Шаг 5. Проверьте гипотезы </br>
        - Средние пользовательские рейтинги платформ Xbox One и PC одинаковые; </br>
        - Средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные.</br>
        - Задайте самостоятельно пороговое значение alpha.</br>
        Поясните:
                - Как вы сформулировали нулевую и альтернативную гипотезы; </br>
                - Какой критерий применили для проверки гипотез и почему. </br>
- Шаг 6. Напишите общий вывод </br>
### Описание данных </br>
Name — название игры </br>
Platform — платформа </br>
Year_of_Release — год выпуска </br>
Genre — жанр игры </br>
NA_sales — продажи в Северной Америке (миллионы проданных копий) </br>
EU_sales — продажи в Европе (миллионы проданных копий) </br>
JP_sales — продажи в Японии (миллионы проданных копий) </br>
Other_sales — продажи в других странах (миллионы проданных копий) </br>
Critic_Score — оценка критиков (максимум 100) </br>
User_Score — оценка пользователей (максимум 10) </br>
Rating — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.</br>
