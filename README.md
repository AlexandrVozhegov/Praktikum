# Яндекс.Практикум. Аналитик данных / Data Analyst
## Мои учебные проекты
|Проект|Задача|Библиотеки|
|---|:--:|---|
|1. Исследование о музыкальных предпочтениях в разных городах России|Как музыка, которая звучит по дороге на работу в понедельник утром, отличается от той, что играет в среду или в конце рабочей недели? Возьмите данные для Москвы и Петербурга.|`pandas`|
|2. Исследование надежности заёмщиков|для решения задачи применялись Лемматизация и Категоризация.|`pandas`|
|3. Исследование объявлений о продаже квартир|Определение рыночной стоимости объектов недвижимости (на базе данных ресурса Яндекс.Недвижимость).|`pandas, matplotlib`|
|4. Определение перспективного тарифа для телеком компании|Анализ тарифов мобильного оператора.Необходимо проанализировать поведение клиентов и сделать вывод — какой тариф лучше.|`pandas, matplotlib.pyplot, math, numpy, scipy`|
|5. Анализ рынка игр.|Определение закономерностей, определяющих успешность игры, и влияющих на будущие рекламные кампании.|`pandas, matplotlib.pyplot, math, numpy, scipy, Mystem, seaborn`|
|6. Аналитика в авиакомпании (Блок SQL)|Понять предпочтения пользователей, покупающих билеты на те или иные направления.|`pandas, matplotlib.pyplot`|
|7. Аналитика в Яндекс.Афише|Расчет бизнес-метрик: Retention, LTV, CAC, ROMI.|`pandas, matplotlib.pyplot, seaborn, math, numpy`|
|8. Анализ результатов A/B теста в интернет магазине|Приоритезация гипотез, запуск A/B-теста и анализ результатов.|`pandas, matplotlib.pyplot, datetime, numpy, scipy`|
|9. Анализ рынка общественного питания Москвы|Исследование рынка общепита|`pandas, numpy, seaborn, matplotlib.pyplot, plotly.express, plotly, numpy, requests`|
|10. Замена шрифтов во всем приложении -  A/A/B-тестирование результатов|Анализ результатов А/A/B теста при изменении шрифтов в приложении.|`pandas, seaborn, matplotlib.pyplot, plotly.express, plotly, scipy, numpy, math`|
|11. Tableau|https://public.tableau.com/profile/alexandr6390#!/vizhome/Bookdataanalysis/Dashboard1?publish=yes||
|12. Прогноз оттока посетителей из сети фитнесс-центров|Построение модели прогнозирования факта оттока посетителей сети фитнесс-центров. Сегментация посетителей.|`pandas, matplotlib.pyplot, seaborn, sklearn, scipy`|

**Задача:** 

**Выводы:** 
   * музыку в двух городах — Москве и Санкт-Петербурге — слушают в разном режиме;
   * списки десяти самых популярных жанров утром в понедельник и вечером в пятницу имеют характерные отличия;
   * население двух городов предпочитает разные музыкальные жанры.
   * 
**Библиотеки:** 


**Задача:** для решения задачи применялись Лемматизация и Категоризация. 

Заказчик — кредитный отдел банка. Нужно разобраться, влияет ли семейное положение и количество детей клиента на факт погашения кредита в срок. Входные данные от банка — статистика о платёжеспособности клиентов. Результаты исследования будут учтены при построении модели кредитного скоринга — специальной системы, которая оценивает способность потенциального заёмщика вернуть кредит банку.

**Вывод:** Идеальный кредитный заемщик:
   * человек с 5тю детьми или вообще без детей
   * ниходится сейчас в браке или был в браке
   * зарплата от 195549.941руб до 2265604.029 руб
   * цель кредита - покупка недвижимости
   * 
**Библиотеки:** `pandas`

### 3. Исследование объявлений о продаже квартир
**Задача:** Определение рыночной стоимости объектов недвижимости (на базе данных ресурса Яндекс.Недвижимость). Установить параметры, которые в той или иной степени оказывают влиение на финальную стоимость. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность.

**Выводы получились интуитивно предсказуемые:** 
* Метраж - Чем больше площадь квартиры, тем выше цена.
* Комнаты - Чем больше комнат, тем выше цена.
* В центре Санкт-Петербурга самые дорогие квартиры.
* На первом этаже самые дешёвые квартиры.

**Библиотеки:** `pandas, matplotlib`

### 
**Задача:**  

**Вывод:** Выручка от пользователей тарифа Ультра больше чем выручка от пользователей тарифа Смарт. Сделать упор в рекламной кампании на 2019 год следует на тариф Ультра.

**Библиотеки:** 

### 
**Задача:** 

**Выводы:** В целом в игровой индустрии: рынок "немобильных" игр постепенно "погибает". Но всеже самое сильное влияние на итоговые продажи игр оказывают оценки критиков. 

**Библиотеки:** 

### 

**Задача:** 

**Выводы:** 
   * 1ое место - Москва.
   * 2ое место с большим отставанием занимает Санкт-Перербург.
   * 3е место - Новосибирск.
   * 
**Библиотеки:** 

### 
**Задача:** Стажировка в отделе аналитики Яндекс.Афиши. Задача: помочь маркетологам оптимизировать маркетинговые затраты. 

**Библиотеки:**

### 
**Задача:** Есть список гипотез для увеличения выручки. 

**Выводы:** После проведения приоритизации гипотез стало ясно что наиболее перспективные, 3 гипотезы из 8ми. В процессе работы с данными была выявлена проблема подглядывания. По результатам A/B тестирования победила руппа B.

**Библиотеки:** 

### 
**Задача:** Решено открыть небольшое кафе в Москве. Оно оригинальное — гостей должны обслуживать роботы. Проект многообещающий, но дорогой. Инвесторов интересует текущее положение дел на рынке — сможет ли кафе снискать популярность на долгое время, когда все зеваки насмотрятся на роботов-официантов? Исследуем рынок. У нас есть открытые данные о заведениях общественного питания в Москве.

**Выводы:** На рынке более популярны кафе, потому именно такой тип заведения и рекомендовать со средним количеством посадочных мест на 30 персон. Касаемо района и улиц, то предполагаем что объект лучше размещать на одной из топ-10 улиц.

**Библиотеки:** 

### 
**Задача:** Изучение воронки продаж в интернет магазине. 

**Выводы:** Гипотеза о том, что изменение всех шрифтов приложения как-то повлияет на наши метрики конверсии, не подтвердилась.

**Библиотеки:** 

### 



### 

**Библиотеки:** 
