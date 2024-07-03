# sber-21-rostelecom
# Data Science Intensive For Rostelecom
Материалы для курса по введению в анализ данных для "Ростелеком".

## Datasets
Данные от "Ростелекома" лежат [тут](https://drive.google.com/drive/folders/1RCjekFXF0Vh1yb3cahKR8n-q7R6k3RXY).

[Датасеты для интенсива](https://disk.yandex.ru/client/disk/rostelecom-sber21)

    ├── raw                             <- Сырые, предоставленные данные от Ростелекома
    │   └── attribute.xlsx              <- Словарь атрибутов (Упрощенная версия для использования)
    │   └── attributes.xlsx             <- Словарь атрибутов
    │   └── 1m, 2m etc.txt              <- Словарь суффиксов атрибутов
    │   └── final_train.csv             <- Данные для обучения
    │   └── final_valid.csv             <- Данные для валидации
    │   └── final_test.csv              <- Данные для теста
    ├── splitted                        <- Разбитые данные для 0ого дня
    │   └── attributes.xlsx             <- Словарь атрибутов (упрощенная версия)
    │   └── suffix.xlsx                 <- Словарь суффиксов
    │   └── appeals_2021_01_03.csv      <- Данные по обращениям 01-03
    │   └── appeals_2021_03_06.csv      <- Данные по обращениям 04-06
    │   └── client_2021_01_03.csv       <- Данные по клиенту 01-03
    │   └── client_2021_04_06.csv       <- Данные по клиенту 04-06
    │   └── failures_2021_01_03.csv     <- Данные по сбоям 01-03
    │   └── failures_2021_04_06.csv     <- Данные по сбоям 04-06
    │   └── geography_2021_01_04.csv    <- Геоданные 01-03
    │   └── geography_2021_04_06.csv    <- Геоданные 04-06
    │   └── iptv_2021_01_03.csv         <- Данные по IPTV 01-03
    │   └── iptv_2021_04_06.csv         <- Данные по IPTV 04-06
    │   └── services_2021_01_03.csv     <- Данные по сервисам 01-03
    │   └── services_2021_04_06.csv     <- Данные по сервисам 04-06
    └─  ...................
### Описание
Датасет состоит из 3 файлов - final_train.csv, final_valid.csv и final_test.csv, для обучения, валидации и тестирования соответственно. \
Кроме фичей для обучения в датасетах добавлены колонки:
* id - уникальные идентификаторы клиентов 
* label - target для обучения, метка реального оттока

## Сопроводительные материалы
Вместе с данными предоставили [ноутбук](../sber-21-rostelecom-tmp/scripts/main.ipynb) с обучением модели оттока. Из полезного там есть ликующие признаки.

Задизайненные презентации [тут](https://drive.google.com/drive/folders/1ZqAgURM4zaH1OdVZ2QgNjxGx5Nosq5Ma?usp=drive_link)


## Projects
Legend: ![](icons/pptx.png) — lection, ![](icons/jupyter.png) — solution,  ![](icons/git.png) — repo

<table>
  <thead>
    <tr>
      <th>День</th>
      <th>Тема</th>
      <th>Jupyter</th>
      <th>Colab</th>
      <th>Материалы</th>
    </tr>
  </thead>
  <tbody>
    <!-------------------- DAY 0 -------------------->
    <tr>
        <td align="center"><a>0</a></td>
        <td align="center">
            Введение в анализ данных. Кто такой DS и чем он занимается. Хранение данных. Виды данных
        </td>
        <td align="center">
            <a href="https://repos.21-school.ru/masters/DSpy00.ID_1421591.git"><img src="./icons/git.png"/></a>
        </td>
        <td align="center">
            <a href="https://repos.21-school.ru/masters/DSpy00.ID_1517611.git"><img src="./icons/git.png"/></a>
        </td>
        <td align="center">
            <a href=".lections/00-01-intro.pptx"><img src="./icons/pptx.png"/></a>
            <a href=".solutions/day-00-solution.ipynb"><img src="./icons/jupyter.png"/></a>
        </td>
    </tr>
  </tbody>
  <tbody>
    <!-------------------- DAY 1 -------------------->
    <tr>
        <td align="center"><a>1</a></td>
        <td align="center">
            Дескриптивный анализ. Описательный статистики. Разведочный анализ. Корреляционный анализ.
            АБ тестирование. Применение Теоремы Байеса.
        </td>
        <td align="center">
            <a href="https://repos.21-school.ru/masters/DSpy01.ID_1421593"><img src="./icons/git.png"/></a>
        </td>
        <td align="center">
            <a href="https://repos.21-school.ru/masters/DSpy01.ID_1517612"><img src="./icons/git.png"/></a>
        </td>
        <td align="center">
            <a href="./lections/01-01-eda.pptx"><img src="./icons/pptx.png"/></a>
        </td>
    </tr>
  </tbody>
  <tbody>
    <!-------------------- DAY 2 -------------------->
    <tr>
        <td align="center"><a>2</a></td>
        <td align="center">
            История машинного обучения. Постановка задачи. Black-Box концепция. 
        </td>
        <td align="center">
            <a href="https://repos.21-school.ru/masters/DSpy02.ID_1421592.git"><img src="./icons/git.png"/></a>
        </td>
        <td align="center">
            <a href="https://repos.21-school.ru/masters/DSpy02.ID_1517613"><img src="./icons/git.png"/></a>
        </td>
        <td align="center">
            <a href="./lections/02-01-ml-intro.pptx"><img src="./icons/pptx.png"/></a>
        </td>
    </tr>
  </tbody>
  <tbody>
    <!-------------------- DAY 3 -------------------->
    <tr>
        <td align="center"><a>3</a></td>
        <td align="center">
            Глубокое обучение
        </td>
        <td align="center">
            <a href="https://repos.21-school.ru/masters/DSpy03.ID_1421594.git"><img src="./icons/git.png"/></a>
        </td>
        <td align="center">
            <a href="https://repos.21-school.ru/masters/DSpy03.ID_1517614.git"><img src="./icons/git.png"/></a>
        </td>
        <td align="center">
            <a href="./lections/03-01-deep-learning.pptx"><img src="./icons/pptx.png"/></a>
        </td>
    </tr>
  </tbody>
  <tbody>
    <!-------------------- DAY 4 -------------------->
    <tr>
        <td align="center"><a>4</a></td>
        <td align="center">
            Внедрение искусственного интеллекта в бизнес процессы
        </td>
        <td align="center">
            <a href="https://repos.21-school.ru/masters/DSpy04.ID_1421595.git"><img src="./icons/git.png"/></a>
        </td>
        <td align="center">
            <a href="https://repos.21-school.ru/masters/DSpy04.ID_1517723.git"><img src="./icons/git.png"/></a>
        </td>
        <td align="center">
        </td>
    </tr>
  </tbody>
</table>
