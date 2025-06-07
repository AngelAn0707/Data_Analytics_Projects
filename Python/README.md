## Проект: Анализ эффективности рекламных кампаний Facebook с помощью Pandas и Python

Описание проекта:

Краткое введение в проект.
В рамках данного проекта проведен анализ данных рекламных кампаний Facebook с использованием библиотеки Pandas в Python и средств визуализации. Цель проекта — исследовать динамику затрат на рекламу, ROMI, поведение отдельных кампаний и взаимосвязи между ключевыми метриками.
Задачи проекта (что вы сделали):

### Задачи:
1. **Загрузка данных:**
Загрузка файлаfacebook_ads_data.csvв DataFrame Pandas.
![image](https://github.com/user-attachments/assets/d5e61fb5-c7d7-4f6b-9419-af87ee265243)

3. **Анализ данных по дням (2021 год):**
Группировка данных по дням.
**График ежедневной суммы затрат на рекламу:** Визуализацияtotal_spendза 2021 год.
![image](https://github.com/user-attachments/assets/4d22dba7-0817-498f-a9f6-47a02100864f)

**График ежедневного ROMI:** ВизуализацияROMIза 2021 год.
![image](https://github.com/user-attachments/assets/157987f0-86ad-49f2-a8b2-4fbe12e9ea1e)

**Бонусное задание:** Применение метода.rolling()для отображения скользящего среднего затрат и ROMI.
![image](https://github.com/user-attachments/assets/9a1553f7-8249-40d0-901b-efeb600f9d28)


5. **Анализ данных по названию кампании:**
Группировка данных по названию кампании (campaign_name).
**График общей суммы затрат на рекламу:** Визуализацияtotal_spendдля каждой кампании.
![image](https://github.com/user-attachments/assets/ac7bc6f8-ffb2-49c5-8fde-acf602f06353)

**График общего ROMI:** ВизуализацияROMIдля каждой кампании.
![image](https://github.com/user-attachments/assets/6b68417a-2267-4982-90e4-497af06dc24e)

7. **Box Plot для ROMI:**
Построение Box Plot для анализа разброса ежедневногоROMIпо каждой кампании, что позволяет выявить аномалии или особенности распределения.
![image](https://github.com/user-attachments/assets/5a9f0adb-421a-4b6d-8e9e-efeee2226be1)

9. **Гистограмма распределения ROMI:**
Построение гистограммы, показывающей распределение значенийROMIпо всему датасету.
![image](https://github.com/user-attachments/assets/88a37266-c2e3-4518-a95c-670927a42408)

11. **Тепловая карта корреляции:**
Построение тепловой карты корреляции между всеми числовыми показателями вfacebook_ads_data.csv.
Идентифицированы показатели с **наивысшей** и **наинизшей** корреляцией.
Определено, с чем наиболее сильно коррелируетtotal_value.
![image](https://github.com/user-attachments/assets/0996eb97-1b8c-4694-a0be-097a47e20237)

13. **Точечная диаграмма с линейной регрессией:**
Построение точечной диаграммы с наложенной линией линейной регрессии (lmplot()) для визуализации взаимосвязи междуtotal_spendиtotal_value.
![image](https://github.com/user-attachments/assets/c07350ea-ae08-4619-8d5a-661ee3ee7711)

Используемые инструменты и библиотеки:

### Используемые инструменты:
* **Python:** Язык программирования.
* **Jupyter Notebook:** Среда разработки для интерактивного анализа.
* **Pandas:** Библиотека для обработки и анализа данных.
* **Matplotlib/Seaborn:** Библиотеки для визуализации данных.
* **facebook_ads_data.csv:** Исходный файл данных.

![Ежедневные затраты на рекламу и ROMI (2021)](images/daily_spend_romi_2021.png)
![Общие затраты на рекламу и ROMI по кампаниям](images/campaign_spend_romi.png)
![Box plot ежедневного ROMI по кампаниям](images/daily_romi_boxplot.png)
![Гистограмма распределения ROMI](images/romi_histogram.png)
![Тепловая карта корреляции](images/correlation_heatmap.png)
![Точечная диаграмма Total Spend vs Total Value](images/spend_value_scatterplot.png)
(Обязательно создайте папку images внутри папки Python_Facebook_Ads_Analysis и сохраните туда все эти скриншоты с соответствующими именами.)
