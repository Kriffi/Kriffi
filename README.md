## О себе

Занимаюсь внедрением и аналитикой в 1С: разбираюсь в бизнес-процессах и собираю требования пользователей.

Пишу проекты на REST API на Go, работаю с PostgreSQL, поднимаю локальное окружение в Docker Compose и проверяю запросы через Postman.

## Мои проекты

### [TodoApp](https://github.com/Kriffi/golang-todoapp)

Учебное веб-приложение на Go и PostgreSQL для управления задачами и просмотра статистики. API описано в Swagger. В репозитории есть SQL-миграции и инструкция по локальному запуску.

**[Открыть сайт TodoApp](https://kriffi-todoapp-be3n.onrender.com/)**

[Код и инструкция по запуску](https://github.com/Kriffi/golang-todoapp#локальный-запуск)

### [Fertility Analysis](https://github.com/Kriffi/Data-Analyst-Pet-Project/tree/main/Fertility%20analysis)

Исследование демографических и социально-экономических показателей стран на данных CIA World Factbook. Подготовил подробный отчёт и интерактивный дашборд Power BI с графиками, картами и фильтрами по регионам. На диаграмме рассеяния исследовал связь между медианным возрастом и рождаемостью.

Для первичной проверки данных использовал **Python (pandas)**. В **Power Query** очистил и объединил таблицы, применив SQL-логику `LEFT JOIN` и нечёткое сопоставление названий стран. Для сводных показателей использовал медиану, минимум и максимум.

[Отчёт со скриншотами](https://github.com/Kriffi/Data-Analyst-Pet-Project/blob/main/Fertility%20analysis/README.md) · [Файл Power BI (.pbix)](https://github.com/Kriffi/Data-Analyst-Pet-Project/blob/main/Fertility%20analysis/Geographic%20Analysis.pbix)

### [EdoConnectorMock](https://github.com/Kriffi/EdoConnectorMock)

Прототип коннектора на **C# / .NET** для интеграции учётной системы, например 1С, с оператором ЭДО. С помощью **XSLT и XPath** преобразует исходный XML учётной системы в XML электронных транспортных накладных (ЭТрН).

### [XmlSerializerApp](https://github.com/Kriffi/XmlSerializerApp)

Консольное приложение на **C# / .NET**. Проверяет ввод, собирает данные в объекты и сохраняет их в XML с помощью `XmlSerializer`.

### [1С BD](https://github.com/Kriffi/1cBD)

Рабочая конфигурация **1С:Предприятие 8.3** для учёта и CRM. В ней можно вести карточки клиентов и историю взаимодействий, оформлять заказы, поступления и платежи, формировать печатные документы и отчёты по продажам. В репозитории есть выгрузка информационной базы `1Cv8.dt` и скриншоты работы системы.
