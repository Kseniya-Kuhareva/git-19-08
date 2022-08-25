# Инструкция по работе с GIT

**Основные команды GIT**:

1. _git init_ - инициализация;
2. _git status_ - инфомация от git о текущем состоянии;
3. _git add_ - добавить файлы к след. коммиту;
4. _git commit_ -m 'message' - создание коммита;
5. _git log_ - вывод на экран истории всех коммитов;
6. _git checkout_ - переход от одного коммита к другому;
7. _git checkout master_ - вернуться к актуальному состоянию и продолжить работу 
8. _git diff_ - увидеть разницу между текущим файлом и закоммиченным файлом.

Еще больше команд по [ссылке](https://habr.com/ru/company/ruvds/blog/599929/)

 # ***Синтаксис языка Markdown***

 - ### Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка  (поддерживается 6 уровней).
- = или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки  первого (“=”) и второго (“-”) уровней.

- ** Полужирное начертание ** или __Полужирное начертание__

- * Курсивное начертание * или _ Курсивное начертание _

- *** Полужирное курсивное начертание ***

- ~~ Зачёркнутый текст ~~

* Строка – ненумерованные списки, символ “*” в начале строки

- 1, 2, 3 … – нумерованные списки/

*Если безанкорные ссылки оформляются двумя угловыми скобками, то для цитаты нужна только одна такая скобка* ( > )
<<<<<<< HEAD
<<<<<<< HEAD
>Чтобы добавить местное изображение
=======
>Чтобы lj,fdbnm местное изображение
>>>>>>> task1
=======
>Чтобы добавить местное изображение
>>>>>>> task2
Вам нужно только указать путь к изображению в скобках базовой грамматики.
![Пример](https://texterra.ru/upload/img/14-01-2020/2/10.png) 


Дополнение к инструкции 
git checkout -b 'name' - создание ветки и переход в нее
git cherry-pick ... - создастся отдельный коммит с изменениями этого коммита

git branch - выводит список веток 
git branch -f ... - передвинуть ярлык по ветке

git commit --amend -m 'edit' - изменяет последний коммит без создания доп коммитов
git log -p - изменения развернуто
