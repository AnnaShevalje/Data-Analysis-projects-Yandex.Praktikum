# Data-Analysis-projects-Yandex.Prakticum-cohort-5
Jypiter notebooks

[Описание сделанных проектов:](#https://nbviewer.jupyter.org/github.com/AnnaShevalje/Data-Analysis-projects-Yandex.Prakticum-cohort-5/blob/master/ECommerce_prinyato.ipynb)

1.  Заказчик – кредитный отдел комменрческого банка. Задача: Анализ клиентов кредитного отдела банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов.
Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.
Использовались следующие навыки: предобработка данных (переименование столбцов, заполнение пропусков, проверка наличия и удаление дубликатов, приведение данных к нужным типам), лемматизация, категоризация данных
Что сделано: проанализированы доли должников в зависимости от доходов и наличия детей, лемматизированы основные цели кредитования, заемщики категоризированы по типу занятости.

2.  Заказчик - Яндекс.Недвижимость. Задача: Исследование сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.
Использовались следующие навыки: предобработка данных (описание аналогично проекту 1), построение гистрограмм, «ящиков с усами», матрицы рассеяния, матрицы корреляций,  описание зависимостей на основе графиков.
Что сделано: проанализирован рынок (локации, стоимость, цена за кВ.метр, зависимости удаленности от центра города, определена граница центра по скачку стоимости кв.метра, проанализированы выбросы цен и корреляции между различными характеристиками объявлений).

3. Заказчик – оператор сотовой связи. Задача: Анализ тарифов федерального оператора сотовой связи. Клиентам предлагают два тарифных плана: «Смарт» и «Ультра». Чтобы скорректировать рекламный бюджет, коммерческий департамент хочет понять, какой тариф приносит больше денег.
Использовались следующие навыки: предобработка данных (описание аналогично проекту 1), построение гистрограмм, проверка гипотез о равенстве средних в выборках 
Что сделано: проанализированы затраты по тарифам, рассчитаны дисперсия, стандартное отклонение, средняя выручка, длительность сессий, проверены гипотезы о равенстве средних в выручках по тарифам.

4. Заказчик – интернет магазин компьютерных игр. Задача: Анализ рынка для интернет-магазина который продаёт по всему миру компьютерные игры. Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Требовалось выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.
Использовались следующие навыки: предобработка данных (описание аналогично проекту 1), построение гистрограмм, проверка гипотез о равенстве средних в выборках, построение гистрограмм, «ящиков с усами», матрицы рассеяния, матрицы корреляций, описание зависимостей на основе графиков (Plotly, Mathplotlib, Seaborn).
Что сделано: проанализированы продажи, рейтинги, популярность и активность выхода игр по платформам, даны рекомендации о наиболее перспективной платформе для запуска игр на будущий период.

5. Заказчик - российская авиакомпания. Задача: Анализ спроса пассажиров на рейсы в города, где проходят крупнейшие фестивали. Выявление зависимостей.
Использовались следующие навыки: парсинг данных, HTML, BeautifulSoup,  get-запросы, SQL, описание зависимостей на основе графиков (Plotly, Mathplotlib, Seaborn).
Что сделано: данные были спарсены из веб ресурса, приведены к формату датафрема и проанализированы, визуализированы, проверены гипотезы о наличии зависимостей.

6. Заказчик – Яндекс.Афиша. Задача: оптимизация маркетинговых затрат по каналам инвестирования.
Использовались следующие навыки: предобработка данных (описание аналогично проекту 1), расчет бизнес метрик (расчет LTV, CAC, RetentionRate, Churn rate, ROMI, DAU/MAU, когортный анализ, построение heatmap, построение гистрограмм, «ящиков с усами»
Что сделано: проанализированы затраты и окупаемости инвестиций по различным каналам и типам источников, даны рекомендации отделу маркетинга по приоритизации инвестиций.

7. Приоритизация гипотез для крупного интернет-магазина. Запуск  A/B-теста и .анализ его результатов
Использовались следующие навыки:  фреймворки  ICE\RICE, выявление наличия статистической значимости при проведении АВ теста, расчет процентилей выборок. 
Что сделано: приоритизированы гипотезы, проведен и проанализирован АВ тест, принато решение по результатам (тест остановлен, статистическая значимость в различии выборок достигнута).

8. Анализ рынка заведений общественного питания города Москва для определения перспективного направления для открытия нового кафе.
Использовались следующие навыки:  предобработка данных (описание аналогично проекту 1), расчета процентилей выборок, построения графиков плотности распределения, гистограмм визуализация Plotly, оформление презентации в РРТ. 
Что сделано: проанализированы заведения общепита по сетевому признаку, количеству посадочных мест, району города, количеству заведений на улице, даны рекомендации, оформлена презентация РРТ.

9. Заказчик – стартап по продаже продуктов питания. Задача – анализ поведения пользователей мобильного приложения (анализ воронки продаж). Исследование результатов АВ теста – о наличии изменений в воронке продаж после изменения шрифта в приложении 
Использовались следующие навыки:  предобработка данных (описание аналогично проекту 1), расчета процентилей выборок, построения гистограмм визуализация Plotly, расчет и отрисовка продуктовой воронки, проверка гипотез Z критерием.(о равенстве долей) – АА и АВ тесты. 
Что сделано: построена воронка продаж клиентов магазина, проверены гипотезы об изменении воронки на основании результатов АВ тестирования.

10. Заказчик – Яндекс.Дзен. Задача – построение автоматизированого обновляемого дашборда для отслеживания взаимодействий пользователей с карточками  Яндекс.Дзен с разбивкой по темам и понимания насколько хорошо пользователи конвертируются из показов карточек в просмотры статей.
Использовались следующие навыки: написание скрипта пайплайна (запись из сырых данных базы в агрегирующие таблицы), кода дашборда (библиотека dash), презентации в РРТ
Что сделано: написан скрипт пайплайна, дашборда, инструкция к тому, как запустить все файлы из виртуальной машины (readme.txt), файл с необходимыми библиотеками (requirements.txt)

11. [Анализ товарного ассортимента интернет-магазина](#https://nbviewer.jupyter.org/github.com/AnnaShevalje/Data-Analysis-projects-Yandex.Prakticum-cohort-5/blob/master/ECommerce_prinyato.ipynb)

Заказчик - интернет-магазина товаров для дома и быта "Пока все ещё тут". Задача - Проанализировать товарный ассортимент. Сегментировать товарный ассортимента на основной и дополнительный. Выработать рекомендации на предмет: какой ассортимент следует закупать магазину в первую очередь, какой во вторую, а на какой вообще не стоит тратиться. Проверить статистические гипотезы. 
Использовались следующие навыки:  предобработка данных (описание аналогично проекту 1), визуализация Plotly, Seaborn. Проверка гипотез Т критерием (о равенстве средних выборок), применение методов ML (кластеризация с использованием библиотеки sklearn.cluster Kmeans, построение дендрограммы).
Что сделано: ассортимент сегментирован на основной и дополнительный, провены статистические гипотезы, ассортимент кластеризирован с применением методов ML,  разработаны рекомендации на предмет: какой ассортимент следует закупать магазину в первую очередь, какой во вторую, а на какой вообще не стоит тратиться.

12. Заказчик – сеть фитнес клубов. Задача: провести анализ и подготовить план действий по удержанию клиентов.
Использовались следующие навыки:  предобработка данных (описание аналогично проекту 1), визуализация Plotly, Seaborn. применение методов ML (кластеризация, , построение дендрограммы, обучение модели прогнозирования оттока клиентов с использованием логистической регрессии, случайного леса, оценка показателей accuracy, precision и recall). Использовальсь библиотеки sklearn.cluster, sklearn.linear, sklearn.tree, sklearn.ensemble, sklearn.metrics, scipy.cluster.hierarchy, sklearn.preprocessing, sklearn.linear_model, sklearn.model_selection и прочие.
Что сделано: Сформулированы основные выводы и предложены рекомендации для стратегии взаимодействия с пользователями и их удержания. Описаны типичные кластеры клиентов, даны рекомендации по работе с наиболее преспрективными из них.

