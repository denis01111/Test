**1**. Умыться
**2**. Помыться
**3**. Позавтракать
# RUSSIAN
# Инструкция по работе с Git
[Выше использованы следующие возможности Markdown: заголовок уровня 1.

Ниже - заголовок уровня 2, цитата, нумерованный и ненумерованный списки, **полужирный шрифт**, _курсив_, ссылка (см. Пункт 4.), ~~зачеркнутый шрифт~~]
## Основные команды
>0. Проверка версии Git
- **git version** - *показывает номер версии, свидетельствует о готовности Git к работе*
>1. Создание проекта
- **git init** - *инициализирует локальный репозиторий Git*

>2. Состояние проекта
- **git status** - *предоставляет информацию о текущем состоянии Git*

- **git add** - *сообщает Git, что Вы хотите включить изменения в файл при следующем коммите*

- **git commit -m "ваш комментарий"** - *создаёт коммит с описанием проделанной работы*

>3. Ветвление и слияние
- **git branch** - _показывает перечень ветвей, активная ветвь отмечена знаком (*)_
- **git branch имя_ветви** - *создаёт новую ветвь*
- **git branch -d имя_ветви** - *удаляет названную ветвь*
- **git checkout имя_ветви** - *перемещает на названную ветвь*
- **git merge имя_ветви** - *производит слияние названной ветви с активную ветвью*

>4. Совместное использование и обновление проектов

- Подробнее смотрите раздел [ Sharing & Updating Projects](https://github.com/joshnh/Git-Commands#sharing--updating-projects) на GitHub.com

>5. Проверка и сравнение
- **git log** - _выводит на экран историю изменений: все коммитов с их хеш-кодами_

- **git log --oneline** - _показывает изменения в кратком виде_
- **git log --summary** - _показывает изменения в подробном виде_

- **git checkout** - _перемещает пользователя между коммитами_

- **git checkout master** - _возвращает файл к актуальному состоянию_

- **git diff** - _позволяет увидеть разницу между текущим файлом уже созраненным, но ещё не закоммиченным файлом с закоммиченным файлом_

  > **NB!** **_git diff_** _работает только после сохранения изменений в редакторе с помощью *Ctrl+S*_  
  _~~В.И. Ленин. Полное собрание сочинений. М: 1925~~_
## Прочие команды
Другие команды смотрите на GitHub по [ссылке](https://github.com/joshnh/Git-Commands#git-commands)  
# ENGLISH
# Instructions for working with Git
[The following Markdown features are used above: Level 1 heading.

Below - level 2 heading, citation, numbered and unnumbered list, **bold**, _italics_, link (see Item 4.), ~~strikethrough~~]
## Basic commands
>0. Checking the Git Version
- **git version** - *shows version number, indicates Git is ready to go*
>1. Create a project
- **git init** - *initializes the local Git repository*

>2. Project status
- **git status** - *provides information about the current state of Git*

- **git add** - *tells Git that you want to include changes to the file on the next commit*

- **git commit -m "your comment"** - *creates a commit with a description of the work done*

>3. Branching and merging
- **git branch** - _shows a list of branches, the active branch is marked with (*)_
- **git branch branchname** - *creates a new branch*
- **git branch -d branchname** - *deletes the named branch*
- **git checkout branchname** - *moves to named branch*
- **git merge branchname** - *merges the named branch into the active branch*

>4. Sharing and updating projects

- See the [ Sharing & Updating Projects](https://github.com/joshnh/Git-Commands#sharing--updating-projects) section on GitHub.com for details

>5. Verification and comparison
- **git log** - _displays the history of changes: all commits with their hash codes_

- **git log --oneline** - _show changes in summary_
- **git log --summary** - _show changes in detail_

- **git checkout** - _moves the user between commits_

- **git checkout master** - _returns the file to its current state_

- **git diff** - _allows you to see the difference between the current file already built, but not yet committed file with the committed file_

  > **NB!** **_git diff_** _works only after saving changes in the editor with *Ctrl+S*_
  _~~V.I. Lenin. Full composition of writings. M: 1925~~_
## Other commands
See other commands on GitHub at [link](https://github.com/joshnh/Git-Commands#git-commands)
# SPANISH
# Instrucciones para trabajar con Git
[Las siguientes funciones de Markdown se utilizan anteriormente: Encabezado de nivel 1.

A continuación: encabezado de nivel 2, cita, lista numerada y sin numerar, **negrita**, _cursiva_, enlace (ver Artículo 4.), ~~tachado~~]
## Comandos básicos
>0. Comprobando la versión de Git
- **git version** - *muestra el número de versión, indica que Git está listo para funcionar*
>1. crear un proyecto
- **git init** - *inicializa el repositorio Git local*

>2. Estado del proyecto
- **git status** - *proporciona información sobre el estado actual de Git*

- **git add** - *le dice a Git que desea incluir cambios en el archivo en la próxima confirmación*

- **git commit -m "tu comentario"** - *crea un commit con una descripción del trabajo realizado*

>3. Ramificación y fusión
- **git branch** - _muestra una lista de ramas, la rama activa está marcada con (*)_
- **git branch branch_name** - *crea una nueva rama*
- **git branch -d branch_name** - *elimina la rama nombrada*
- **git checkout branchname** - *se mueve a la rama nombrada*
- **git merge branch_name** - *fusiona la rama nombrada en la rama activa*

>4. Compartir y actualizar proyectos

- Consulte la sección [Compartir y actualizar proyectos](https://github.com/joshnh/Git-Commands#sharing--updating-projects) en GitHub.com para obtener más información.

>5. Verificación y comparación
- **git log** - _muestra el historial de cambios: todas las confirmaciones con sus códigos hash_

- **git log --oneline** - _mostrar cambios en resumen_
- **git log --summary** - _mostrar cambios en detalle_

- **git checkout** - _mueve al usuario entre confirmaciones_

- **git checkout master** - _devuelve el archivo a su estado actual_

- **git diff** - _le permite ver la diferencia entre el archivo actual ya creado, pero el archivo aún no confirmado con el archivo confirmado_

  > **¡NOTA!** **_git diff_** _funciona solo después de guardar los cambios en el editor con *Ctrl+S*_
  _~~V.I. lenin Composición completa de escritos. M: 1925~~_
# Polish
# Instrukcje dotyczące pracy z Git
[Poniższe funkcje Markdown są używane powyżej: Nagłówek poziomu 1.

Poniżej - nagłówek poziomu 2, cytat, lista numerowana i nienumerowana, **pogrubienie**, _kursywa_, link (patrz punkt 4.), ~~przekreślenie~~]
## Podstawowe polecenia
>0. Sprawdzanie wersji Git
- **git version** - *pokazuje numer wersji, wskazuje, że Git jest gotowy do pracy*
>1. Utwórz projekt
- **git init** - *inicjuje lokalne repozytorium Git*

>2. Stan projektu
- **git status** - *zapewnia informację o aktualnym stanie Git*

- **git add** - *mówi Gitowi, że chcesz uwzględnić zmiany w pliku przy następnym zatwierdzeniu*

- **git commit -m "twój komentarz"** - *tworzy commit z opisem wykonanej pracy*

>3. Rozgałęzianie i łączenie
- **git branch** - _pokazuje listę oddziałów, aktywny oddział jest oznaczony (*)_
- **git branch_name** - *tworzy nowy oddział*
- **git branch -d branch_name** - *usuwa nazwaną gałąź*
- **git checkout branch_name** - *przechodzi do nazwanej gałęzi*
- **git merge branch_name** - *scala nazwaną gałąź z gałęzią aktywną*

>4. Udostępnianie i aktualizowanie projektów

- Zobacz sekcję [ Udostępnianie i aktualizowanie projektów](https://github.com/joshnh/Git-Commands#sharing--updating-projects) na GitHub.com, aby uzyskać szczegółowe informacje

>5. Weryfikacja i porównanie
- **git log** - _wyświetla historię zmian: wszystkie zatwierdzenia z ich hash kodami_

- **git log --oneline** - _pokaż zmiany w podsumowaniu_
- **git log --summary** - _pokaż szczegóły zmian_

- **git checkout** - _przenosi użytkownika między zatwierdzeniami_

- **git checkout master** - _przywraca plik do aktualnego stanu_

- **git diff** - _pozwala zobaczyć różnicę między bieżącym plikiem już zbudowanym, ale jeszcze niezatwierdzonym, a plikiem zatwierdzonym_

  > **NB!** **_git diff_** _działa tylko po zapisaniu zmian w edytorze za pomocą *Ctrl+S*_
  _~~V.I. Lenin. Pełny skład pism. M: 1925~~_
## Inne polecenia
Zobacz inne polecenia na GitHub pod adresem [link](https://github.com/joshnh/Git-Commands#git-commands)
# JAPANESE
# Gitを操作するための手順
[上記では次のマークダウン機能が使用されています：レベル1の見出し。

以下-レベル2の見出し、引用、番号付きおよび番号なしのリスト、**太字**、_イタリック_、リンク（項目4を参照）、~~取り消し線~~]
## 基本コマンド
>0. Gitバージョンの確認
- **git version** _バージョン番号を表示します。Gitの準備ができていることを示します_

>1. プロジェクトを作成する
- **git init** _ローカルGitリポジトリを初期化します_

>2. プロジェクトステータス
- **git status** _Gitの現在の状態に関する情報を提供します_

- **git add** _-*_次のコミット時にファイルへの変更を含めることをGitに通知します_*_

- **git commit -m"あなたのコメント"** _実行された作業の説明を含むコミットを作成します_

>3. 分岐とマージ
- **git branch** _ブランチのリストを表示し、アクティブなブランチは（*）でマークされます_
- **git branch branch_name** _新しいブランチを作成します_
- **git branch -d branch_name** _指定されたブランチを削除します_
- **git checkout branch_name** _-*_名前付きブランチに移動します_*_
- **git merge branch_name** _指定されたブランチをアクティブなブランチにマージします_

>4. プロジェクトの共有と更新

- 詳細については、GitHub.comの [プロジェクトの共有と更新]（https://github.com/joshnh/Git-Commands#sharing--updating-projects）セクションを参照してください

>5. 検証と比較
- **git log** _変更の履歴を表示します：すべてのコミットとハッシュコード_

- **git log --oneline** _変更を概要に表示_
- **git log --summary** _変更の詳細を表示_

- **git checkout** _コミット間でユーザーを移動します_

- **git checkout master** _ファイルを現在の状態に戻します_

- **git diff** _すでにビルドされているが、まだコミットされていないファイルとコミットされたファイルの違いを確認できます_

  > **NB!** **_git diff_** _は *Ctrl+S* を使用してエディターで変更を保存した後にのみ機能します
  ~~ウラジーミル・レーニン. 文章の完全な構成. M：1925~~_

## その他のコマンド
[リンク]（https://github.com/joshnh/Git-Commands#git-commands）でGitHubの他のコマンドを参照してください
＃＃ オフトピック
catphoto
！[猫がクマの耳を噛んだ]（Samba.jpg)
# Off topic
catphoto
![The cat bit the bear's ear](Samba.jpg)
# 
# ВСЕГО ВАМ ДОБРОГО, ХОРОШЕГО НАСТРОЕНИЯ И ЗДОРОВЬЯ