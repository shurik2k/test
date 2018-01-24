## Описание

Нужно сделать страницу, где будет форма загрузки базы данных в формате JSON

После загрузки нужно  сделать таблицу с динамическими колонками (может быть разное кол-во, в зависимости от импортируемого файла), соответствующие полям в json файле + колонка с действиями (изменить, удалить)

При нажатии на “переименовать” происходит смена содержимого строки таблицы на инпуты с уже вбитыми данными и кнопкой сохранить. 

Необходимо все выполнить с помощью react и redux 

Примерный вид:
![Пример](/screenshot.png)

Пример файла
```json
[
  {
    "candidateName":"Peter Petrov",
    "candidateStatus":"pending",
    "candidateNeedOffer":1800
  },
  {
    "candidateName":"Ivan Ivanov",
    "candidateStatus":"pending",
    "candidateNeedOffer":3000
  },
  {
    "candidateName":"Roman Romanov",
    "candidateStatus":"oninterview",
    "candidateNeedOffer":2400
  },
  {
    "candidateName":"Konstantin Konstantinov",
    "candidateStatus":"on_test_perdiod",
    "candidateNeedOffer":3000
  }
]
```
