# GitLearning
*homework 1*
***
> Git — система контроля версий (файлов). Что-то вроде возможности сохраняться в компьютерных играх (в Git эквивалент игрового сохранения — коммит). 
> Важно: добавление файлов к «сохранению» двухступенчатое: сначала добавляем файл в индекс (git add), потом «сохраняем» (git commit).

> Любой файл в директории существующего репозитория может находиться или не находиться под версионным контролем (отслеживаемые и неотслеживаемые).

> Отслеживаемые файлы могут быть в 3-х состояниях: неизменённые, изменённые, проиндексированные (готовые к коммиту).

Перед началом работы нужно выполнить некоторые настройки:
* git config --global user.name «Ваше имя английскими буквами» 
* git config --global user.email ваша почта@example.com

**Команды**
- git –version  # показывает версию
- git init # инициализация
- git status # статус
- git add  ‘file’ # отслеживание
- git add . # отследить все файлы
- git commit –m “комментарий” # фиксация, сохранение
- git log # журнал изменений, выход q
- git checkout ***** # переход к какой либо версии, можно ввести первые четыре знака сохранения
- git commit –am “text” # коммит без add
- git master # переход к актуальной версии
- git diff # показывает не отслеженные изменения (сохраненные)

## Полезные ссылки
[Git для новичков (часть 1)](https://habr.com/ru/post/541258/)

[Git для новичков (часть 2)](https://habr.com/ru/post/542616/)

[Настройка репозитория](https://www.atlassian.com/ru/git/tutorials/setting-up-a-repository)

[Сохранение изменений](https://www.atlassian.com/ru/git/tutorials/saving-changes)

[Git status: проверка репозитория](https://www.atlassian.com/ru/git/tutorials/inspecting-a-repository)

[Отмена коммитов и изменений ](https://www.atlassian.com/ru/git/tutorials/undoing-changes)

[Руководство по оформлению файлов Markdown](https://gist.github.com/Jekins/2bf2d0638163f1294637#Links)
