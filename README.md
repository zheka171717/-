# Что такое Git
git - это система для управления версиями исходного кода программ. 1 Она позволяет отслеживать любые изменения в файлах, хранить их версии и оперативно возвращаться в любое сохранённое состояние. 2

Git помогает разработчикам параллельно работать над проектом, не мешать друг другу и добавлять в основную ветку только качественный код.
# Справка по работе с git
## Как скачать и что делать 
1) Скачиваем установочный файл git с официального сайта для Windows, MAC, Linux: https://git-scm.com/downloads
2) Скачиваем VSCode для Windows, MAC, Linux: https://code.visualstudio.com/Download для более комфортной работы.
3) после установки git в терминале VScode прописываем команду git --version если у вас появится сообщение git version 2.48.1.windows.1 (версия может отличатся) то вы установили все правильно
4) Чтобы git заработал в репозитории нужно прописать в терминале команду "git init" так в репозитории появится скрытый файл .git после этого можно приступать к работе с git-ом
### Команды для работы с git
* git init – инициализация локального репозитория
* git status – получить информацию от git о его текущем состоянии
* git add – добавить файл или файлы к следующему коммиту
* git commit -m “message” – создание коммита.
* git log – вывод на экран истории всех коммитов с их хеш-кодами
* git checkout – переход от одного коммита к другому
* git checkout master – вернуться к актуальному состоянию и продолжить работу
* git diff – увидеть разницу между текущим файлом и закоммиченным файлом
### Git использует синтаксис языка Markdown вот основные команды
"###" Заголовок – выделение заголовков. Количество символов “#” задаёт уровень заголовка (поддерживается 6 уровней)
Пример 
# пример 1
## пример 2
### пример 3
#### пример 4
##### пример 5
###### пример 6
"=" или "-" – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого (“=”) и второго (“-”) уровней.
##### Полужирное начертание или Полужирное начертание ** или __ в начале и в конце строки
##### *Курсивное начертание* или _Курсивное начертание_ * или _ в начале и в конце строки
###### *Полужирное курсивное начертание* -"***" с начала строки и также 3 в конце
###### Зачёркнутый текст  - "~" в начале и в конце строки
* " * " Строка – ненумерованные списки, символ “*” в начале строки (эта же строчка является примером)
1, 2, 3 … – нумерованные списки ( пример в разделе как скачать)
