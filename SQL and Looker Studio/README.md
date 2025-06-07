Описание проекта:

Краткое введение в проект.
В рамках данного проекта был разработан интерактивный дашборд в Google Looker Studio (ранее Google Data Studio) для анализа ключевых метрик эффективности маркетинговых кампаний. Цель дашборда — предоставить наглядное представление о расходах на рекламу (Ad Spend), возврате инвестиций (ROMI) и других важных показателях, чтобы помочь в принятии обоснованных решений по оптимизации кампаний.
Задачи проекта (что вы сделали):

### Задачи:
1. Подключение к базе данных PostgreSQL с использованием "Custom Query" для получения сырых данных.
2. Создание расчетных полей: Сумма Ad Spend, CPC (Cost Per Click), CPM (Cost Per Mille), CTR (Click-Through Rate), ROMI (Return On Marketing Investment).
3. Построение трех ключевых визуализаций:
Комбинированная диаграмма: Ad Spend и ROMI по месяцам.
Линейный график: Количество активных кампаний по месяцам.
Таблица: Детализация кампаний с Ad Spend, CPC, CPM, CTR, ROMI и тепловыми картами.
4. Добавление интерактивных фильтров по названию кампаний и дате показа рекламы.
Используемые инструменты и технологии:

### Используемые инструменты:
* **Google Looker Studio:** Для создания дашборда и визуализации данных.
* **PostgreSQL:** Источник данных.
* **SQL:** Для выполнения кастомного запроса и подготовки данных.
Ключевые метрики и расчеты:

### Расчетные поля:
* **Ad Spend:** Сумма затрат на рекламу.
* **CPC (Cost Per Click):**Ad Spend / Clicks``
* **CPM (Cost Per Mille):**Ad Spend / (Impressions / 1000)``
* **CTR (Click-Through Rate):**(Clicks / Impressions) * 100``
* **ROMI (Return On Marketing Investment):**(Revenue - Ad Spend) / Ad Spend * 100``
![image](https://github.com/user-attachments/assets/10551b4b-2a7a-4e1d-89de-28d05f120e71)
![image](https://github.com/user-attachments/assets/099d85f0-941b-4406-8e13-050a52882126)
![image](https://github.com/user-attachments/assets/dd101cab-a264-4f5a-8259-6b7fd271472f)
![image](https://github.com/user-attachments/assets/52824c38-f3c6-45da-95d6-571d60ab8642)
