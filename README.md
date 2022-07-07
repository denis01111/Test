# Инструкция

## Выделение текста

Чтобы выделить текст курсивом, обрамляем его звездочками (*) или знаком нижнего подчеркивания (_)
*Курсив*  _Курсив_

Чтобы выделить текст полужирным, обрамляем его двойными звездочками (**) или двойным знаком нижнего подчеркивания (__)
**Полужирный**  __Полужирный__

Альтернативные способы выделения текста жирным или курсивом нужны для того, чтобы мы могли совмещать оба этих способа, например, текст может быть курсивом и полужирным, _**например**_

## Cписки

Чтобы выделить списки - (*)

Для ненумерованных списков используется выделение пунктов звездочкой или знаком +
Например:
* Элемент 1
* Элемент 2
* Элемент 3

Чтобы добавить нумерованные списки, необходимо просто пронумеровать списки
1. Первый пункт
2. Второй пункт
3. Третий пункт

## Изображения

Чтобы вставить изображения в текст достаточно написать следующее

![Рабочая картинка](Рисунок1.png)

## Ссылки

[лекция 1](https://gbcdn.mrgcdn.ru/uploads/asset/3937510/attachment/187904bc7fa424abc113f5dda8b497ff.pdf "Лекция 1")

## Таблицы

|Столбец1|Столбец2|Столбец3|
|--------|:------:|:------:|
|Строка 1 |Строка 1 |Строка 1 |
|Строка 2 |Строка 2 |Строка 2 |
|Строка 3 |Строка 3 |Строка 3 |

## Цитаты

Для того, чтобы создать цитату, необходимо использовать угловую скобку(знак больше) в начале строки
> Цитата
>>Вложенная цитата

## Подсветка кода и выделение элементов

Для выделения блока текста с кодом можно использовать тройные апострофы, если необходимо выделить одно `слово`, то просто обрамить его апострофами

```javascript
let greeting1 ='Father';
console.log(greeting1);
let greeting2 = 'Mother';
console.log(greeting2);

```

```python
x = int(input())
if x > 0:
    print(x)
else:
    print(-x)
```

## GitHub

Для работы с GitHub необходимо для начала создать аккаунт. Затем создать локальный и удаленный репозитории.
Чтобы скопировать внешний репозиторий на свой пк, используется команда: git clone ссылка_на_репозиторий.
Команда git pull ссылка_на_репозиторий выкачивает всё из репозитория и слить с текущей веткой.
Команда git push ссылка_на_репозиторий закачивает наш репозитоий на GitHub (в данном пункте необходима авторизация).

## Заключение

Язык маркдаун позволяет удобно работать с текстом. Несмотря на то, что существуют более удобные инструменты работы с текстом, данный язык пригоден для машинного преобразования в языки для продвинутых публикаций (HTML, Rich Text и других).