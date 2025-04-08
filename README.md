# Домашнее задание к занятию "Процессы, управление процессами "
### Золоторев Н.Д.

### Задание 1
Измените команду ls /tmp /tmp1так, чтобы:

    Результат работы (список файлов) для текущего запуска команды выводился в файл /tmp/file_list.
    Ошибки для каждого запуска добавлялись в файл /tmp/file_errors.

Примечание к заданию:

    Создавать /tmp1 не требуется. Директория должна отсутствовать для генерации вывода stderr.
    Задание необходимо выполнить одной командой.

В качестве решения пришлите полученную команду и скриншот терминала с выводом содержимого созданных файлов

### Решение 1

ls /tmp /tmp1 1>/tmp/file_list 2>/tmp/file_errors

<img src = "img/ls_tmp.png" width = 100%>

cat /tmp/file_list

<img src = "img/file_list.png" width = 100%>

cat /tmp/file_errors

<img src = "img/file_errors.png" width = 100%>

### Задание 2

Напишите команду, которая выводит все запущенные процессы пользователя root в файл "user_root_ps".

### Решение 2

ps -U root 1>user_root_ps

<img src = "img/cat_user_root_ps_1.png" width = 100%>

<img src = "img/user_root_ps2.png" width = 100%>

<img src = "img/user_root_ps3.png" width = 100%>

<img src = "img/user_root_ps4.png" width = 100%>

<img src = "img/user_root_ps5.png" width = 100%>

### Задание 3
### Решение 3
