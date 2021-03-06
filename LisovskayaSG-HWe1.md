# Контроль версий с Git
## __Команды Git__

### Команда *git init*
* Инициализация: указываем папку, в которой git начнёт отслеживать изменения;
* В папке создаётся скрытая папка .git.

### Команда *git status*
* Показывает текущее состояние гита, есть  ли изменения, которые нужно закоммитить (сохранить).

### Команда *git add*
* Добавляет содержимое рабочего каталога  в индекс (staging area) для последующего коммита. Эта команда дается после добавления файлов. Писать название целиком не обязательно: терминал дозаполнит данные автоматически.

### Команда *git commit -m “message”*
* Зафиксировать или сохранить.

### Команда *git log*
* Журнал изменений;
* Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений.

### Команда *git log --graph*
* Визуализирует граф коммитов - отображает ASCII граф с ветвлениями и историей слияний c выводом лога.

### Команда *git checkout*
* Переключение между версиями;
* Для работы нужно указать не только интересующий вас коммит, но и вернуться  в тот, где работаем, при помощи команды  git checkout master.

### Команда *git diff*
* Показывает разницу между текущим файлом и сохранённым;
* Перед переключением версии файла в Git используйте команду git log, чтобы увидеть количество сохранений.

### Команда *git branch*
* Выводит список веток;
* Создает новую ветку.

### Команда *clear*
* Чистит терминал

### Команда *git merge*
* Чтобы слить любую ветку с текущей, вызываем git merge <имя ветки для слияния с текущей>.

### Команда *git clone*
* Копирование внешнего репозитория на свой ПКж
* Загружает все изменения и пытается слить все ветки на локальном компьютере и в удаленном репозитории.

### Команда *git push*
* Отправляет свою версию репозитория во внешний репозиторийж
* ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории.

### Команда *pull request*
* Педлагает измененияж
* Передает запрос на вливание изменений в репозиторий.
***

## Как настроить совместную работу 

1. Создать аккаунт на GitHub.com 
2. Создать локальный репозиторий 
3. “Подружить” ваш локальный и удалённый репозитории. GitHub при создании нового репозитория подскажет, как это можно сделать 
4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно,  вам нужно будет авторизоваться на удалённом репозитории 
5. Провести изменения “с другого компьютера” 
6. Выкачать (pull) актуальное состояние из удалённого репозитория
***
## Как сделать pull request fork 
* Делаем __fork__ (ответвление) репозитория 
* Делаем git clone своей версии репозитория
* Создаем новую ветку и в нее вносим свои изменения 
* Фиксируем изменения (делаем коммиты) 
* Отправляем свою версию в свой GitHub 
* На сайте GitHub нажимаем кнопку pull request

***
*Нажатие клавиши ‘q’ возвращает  в исходное окно терминала.*
***
*Чтобы вызвать ранее введённую команду, пользуемся стрелками на клавиатуре. Перебираем недавно введённые команды нажатием стрелки «вверх».*
***

## __Синтаксис языка Markdown__
1. _Заголовоки и подзаголовки_ выделяются знаком "#". Количество символов "#" задаёт уровень заголовка/подзаголовка. Максимальное допустимое количество уровней - 6. Также знаки "=" или "-" не менее 3 подряд, выделяют заголовки  первого (“=”) и второго (“-”) уровней.

2. _Полужирное начертание_ можно получить если выделить слово/фразу знаками "**" с двух сторон. Также полужирного начертания можно достигнуть путём выделения слова/фразы знаками "__" с двух сторон.

3. _Курсивное начертание_ можно получить если выделить слово/фразу знаком "*" с двух сторон. Также курсивного начертания можно достигнуть путём выделения слова/фразы знаком "_" с двух сторон.

4. _Полужирное курсивное начертание_ можно получить если выделить слово/фразу знаками "***" с двух сторон.

5. Начертание _зачеркнутого текста_ можно получить если выделить слово/фразу знаком "~" с двух сторон.

6. _Цитирование_ обозначантся наком ">" в начале строки. Количество символов ">" задает уровни цитирования. Максимально допустимое количество уровней - 15.

### __Списки__

1. Ненумерованные списки задаются знаком "*" в начале строки.
* Пункт 1
* Пункт 2
* Пункт 3

2. Нумерованные списки задаются числом (номером 1,2,3..) подпункта.
1) Пункт 1
2) Пункт 2
3) Пункт 3

***
# Примеры использования
> *Цитата какого-то важного выражения.*

[Статья про котиков на Вики](https://ru.wikipedia.org/wiki/%D0%9A%D0%BE%D1%88%D0%BA%D0%B0)

## Использование изображений в языке Markdown
Чтобы вставить изображение в текст нужно написать: ![текст, который будет выводится, если изображение не будет отображаться](имя файла, из которого нужно достать изображение)

### Пример:
![Котик](cat.jpg)

***