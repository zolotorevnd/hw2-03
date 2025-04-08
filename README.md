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
### Решение 2

### Задание 3
### Решение 3
