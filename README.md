# Шпаргалка.Cписок команд и понятий для Git.

## Список команд.

"pwd" - Узнать в какой папке находимся.


"cd ~" - Перейти к домашней директории.

"ls" - Вывести содержимое директории.

"cd" - Сменить директорию. (Если в названиях есть пробелы нужны ковычки, чтобы вернуться в родительскую директорию, можно поставить две точки.)

"touch %название файла%" - Создать файл.

"mkdir %Имя папки%" - Создать папку.

"cp что_копировать куда_копировать /" - Копирование файла.

"mv что_перенести куда_перенести" - Перенос файла.

"cat %название файла%" - Чтение файла.

"rm %название файла%" - Удаление файла.

"rmdir %название папки%" - Удаление папки. (Если в ней нету файлов "rm -r %название папки% удалит папку со всем её содержимым")

"git init" - Сделать папку репозиторием.

"git status" - Проверить состояние репозитория.

"git add (git add --all)" - Подготовить файл/все файлы к сохранению.

"git commit -m %"описание"%" - Выполнить коммит.

"git log" - Просмотреть историю коммитов.

"git remote add" - Привязать удаленный репозиторий к локальному.

"git push/git push -u origin master(первый раз)" - Отправить изменения на удаленный репозиторий.