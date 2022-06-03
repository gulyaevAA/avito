# Avito
Описание пет-проекта.



## Цель:
- Отправка сообщения, содержащего прогнозную рыночную стоимость жилой недвижимости в зависимости от переданных параметров квартиры, пользователю используя телеграм-бот.

## Задачи:
1. парсинг данных с avito.ru и создание датасета;
1. обработка датафрейма;
1. подготовка и отбор признаков к моделированию;
1. построение модели и ее корректировка;
1. развертывание модели в тг-боте.

## Этапы:
1. [*Парсинг данных и создание датасета*](https://github.com/gulyaevAA/pet-projects/blob/main/Avito/Parsing-and-creating-df.ipynb)
1. [*Feature engineering и построение модели*](https://github.com/gulyaevAA/pet-projects/blob/main/Avito/FE-and-ML.ipynb)
1. [*Создание тб-бота*](https://github.com/gulyaevAA/pet-projects/blob/main/Avito/tg-bot.ipynb)

### Результат 1 этапа *Парсинг данных и создание датасета*
Получен датафрейм [database.csv](https://github.com/gulyaevAA/pet-projects/blob/main/Avito/database_with_district.csv)

### Результат 2 этапа *Feature engineering и построение модели*
Сохранены две модели для [прогнозирования цены](https://github.com/gulyaevAA/pet-projects/blob/main/Avito/model_price.pkl) и [подбора ссылок на похожие объекты](https://github.com/gulyaevAA/pet-projects/blob/main/Avito/model_links.pkl)
Сохранены датафреймы для использования их на следующем этапе. [Датасет](df_all_features.csv) для прогнозирования цены и [датасет](./database_with_links.csv) для отправки ссылок

### Результат 3 этапа *Создание тб-бота*
Рабочий тг-бот для прогнозирования цены и отправки ссылки на похожие объекты
|  |  |
| :---: | :---: |
|![](./Images/tg-bot-1.png)  |  ![](./Images/tg-bot-2.png) |
|![](./Images/tg-bot-3.png)  |  ![](./Images/tg-bot-4.png) |
|![](./Images/tg-bot-5.png)  |  ![](./Images/tg-bot-6.png) |

<img src="./Images/tg-bot-7.png" width="800"/>