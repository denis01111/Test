# Введение в контроль версий

## Основные команды Git

- **git init** – инициализация локального репозитория

- **git status** – получить информацию от git о его текущем состоянии

- **git add** – добавить файл или файлы к следующему коммиту

- **git commit -m “message”** – создание коммита.

- **git log** – вывод на экран истории всех коммитов с их хеш-кодами

- **git checkout** – переход от одного коммита к другому

- **git checkout master** – вернуться к актуальному состоянию и продолжить работу

- **git diff** – увидеть разницу между текущим файлом и закоммиченным файлом

## Синтаксис языка Markdown

### Выделение текста

- (#) Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка
(поддерживается 6 уровней).

- = или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки
первого (“=”) и второго (“-”) уровней.

- ** Полужирное начертание(**) или __ Полужирное начертание__


- (*) Курсивное начертание  или _Курсивное начертание_

- (~~) Зачёркнутый текст 

### Списки

ЧТобы добавить ненумерованные списки, необходимо пункты выделить (*) или знаком (+)
* Элемент 1
* Элемент 2
* Элемента 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты пронумеровать
1. Первый пункт
2. Второй пункт

Чтобы добавить многоуровневые списки необходимо каждый новый подпункт выделять табуляцией.

- Пункт 1

        - Подпункт A

                - Подподпункт a


- Пункт 2

        + Подпункт A

                * Подподпункт a


### Работа с изображениями

Чтобы вставить изображение в текст необходимо:
![это мост](bridge.jpg)


### Работа с таблицами

Для создания таблицы в Markdown необходимо использовать тире - и вертикальные полосы | для разделения строк и столбцов.

| Столбец | Столбец |
| ------- | ------- |
| ------- | ------- |
| ------- | ------- |


## Работа с удаленными репозиториями

### Основные команды

- **git clone** - команда позволяет склонировать внешний репозиторий на наш ПК.

- **git pull** - команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией.

- **git push** - команда позволяет отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории.

### Как сделать pull request

1. Делаем fork репозитория.

2. Делаем clone СВОЕЙ версии репозитория.

3. Создаем новую ветку и в НЕЕ вносим свои изменения.

4. Фиксируем изменения (делаем коммиты).

5. Отправляем свою версию в свой GitHub.

6. На сайте GitHub нажимаем кнопку pull request.

