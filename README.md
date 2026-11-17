## О себе

Занимаюсь внедрением и аналитикой в 1С: разбираюсь в бизнес-процессах и собираю требования пользователей. Хочу перейти в backend-разработку на Go.

На учебных проектах пишу REST API на Go, работаю с PostgreSQL, поднимаю локальное окружение в Docker Compose и проверяю запросы через Postman.

## Мои проекты

### [Fertility Analysis](https://github.com/Kriffi/Data-Analyst-Pet-Project/tree/main/Fertility%20analysis)

Исследование демографических и социально-экономических показателей стран на данных CIA World Factbook. Подготовил подробный отчёт и интерактивный дашборд Power BI с графиками, картами и фильтрами по регионам. На диаграмме рассеяния исследовал связь между медианным возрастом и рождаемостью.

Для первичной проверки данных использовал **Python (pandas)**. В **Power Query** очистил и объединил таблицы, применив SQL-логику `LEFT JOIN` и нечёткое сопоставление названий стран. Для сводных показателей использовал медиану, минимум и максимум.

[Отчёт со скриншотами](https://github.com/Kriffi/Data-Analyst-Pet-Project/blob/main/Fertility%20analysis/README.md) · [Файл Power BI (.pbix)](https://github.com/Kriffi/Data-Analyst-Pet-Project/blob/main/Fertility%20analysis/Geographic%20Analysis.pbix)

### [TodoApp](https://github.com/Kriffi/golang-todoapp)

Учебное веб-приложение на Go и PostgreSQL для управления задачами и просмотра статистики. API описано в Swagger. В репозитории есть SQL-миграции и инструкция по локальному запуску.

[Демо на Render](https://kriffi-todoapp-be3n.onrender.com/) · [Код и запуск](https://github.com/Kriffi/golang-todoapp#локальный-запуск)

### [EdoConnectorMock](https://github.com/Kriffi/EdoConnectorMock)

Прототип коннектора на **C# / .NET** для интеграции учётной системы, например 1С, с оператором ЭДО. С помощью **XSLT и XPath** преобразует исходный XML учётной системы в XML электронных транспортных накладных (ЭТрН).

### [XmlSerializerApp](https://github.com/Kriffi/XmlSerializerApp)

Консольное приложение на **C# / .NET**. Проверяет ввод, собирает данные в объекты и сохраняет их в XML с помощью `XmlSerializer`.
