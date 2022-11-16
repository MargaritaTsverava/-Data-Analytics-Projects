## Тема: Выпускной проект

Выпускной проект состоит из 3 частей:
* составление декомпазиции проекта, анализ данных 
* обработка результатов A/B-тестирования
* SQL

## Проект 1: Определение неэффективных операторов телеком-компании «Нупозвони»

### Задача проекта: 
Необходимо определить самых неэффективных операторов по определенным признакам низкой эффективности.

### Используемые инструменты и методы:
* библиотеки: pandas, numpy, seaborn, matplotlib, plotly
* обзор данных: info(), head()
* предобработка и анализ данных: duplicated(), drop_duplicates(), dropna(), isna(), nunique(), groupby(), to_datetime(), describe(), pivot_table(), merge()
* построение графиков: scatterplot(), Pie(), hist(), boxplot()

Подготовлены [дашборд](https://public.tableau.com/app/profile/margarita7955/viz/_16640114853260/sheet2?publish=yes) и [презентация](https://drive.google.com/file/d/13LL9kAXH6XPgBHtB6b_h1HCJ0XnI3gpg/view?usp=sharing) для целей автоматизации работы менеджеров.

## Проект 2: Оценка результатов A-B-теста

### Задача проекта:
Оценить корректность проведения теста, проанализировать результаты теста.

### Используемые инструменты и методы:
* библиотеки: pandas, plotly, seaborn, matplotlib, math, scipy
* обзор данных: info(), head()
* предобработка и анализ данных: to_datetime(), duplicated(), isna(), unique(), nunique(), merge(), query(), groupby(), reset_index()
* построение графиков: Pie(), barplot(), countplot(), Funnel()
* проверка статистической значимости: z_value

## Проект 3: SQL

### Задача проекта:
Проанализировать базу данных и выполнить запросы.

### Используемые инструменты и методы:
* подключение к БД: create_engine()
* чтение запросов SQL: pd.io.sql.read_sql()
* SQL: SELECT, WHERE, JOIN, GROUP BY, HAVING, WITH, ORDER BY



