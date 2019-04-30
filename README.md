# OlympiadNotifierAPI
API для получения информации об олимпиадах и других мероприятий для школьников в виде JSON объектов.

## Получить список предстоящих событий
```http://94.103.83.68/getNext?class={class}&subject={subject}&stage={stage}```

## Получить список текущих событий
```http://94.103.83.68/getCurrent?class={class}&subject={subject}&stage={stage}```

| Параметр запроса | Описание |
| ------------- | ------------------------------ |
| `class` | Класс обучения (5-11) |
| `subject` | Школьный предмет из списка |
| `stage` | "selection" для отборочных этапов, "final" - для заключительных |

## Список поддерживаемых предметов
+ mathematics (Математика)
+ informatics (Информатика)
+ russian (Русский язык)
+ physics (Физика)
+ chemistry (Химия)
+ biology (Биология)
+ social (Обществознание)
+ literature (Литература)
+ geography (География)
+ foreign (Иностранные языки)
+ art (Искусство)
+ economy (Экономика)
+ -1 (Любой предмет)
