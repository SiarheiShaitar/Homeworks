1) Посмотреть где я === pwd

2) Создать папку === mkdir foldername

3) Зайти в папку === cd foldername

4) Создать 3 папки === mkdir foldername1 foldername2 foldername3

5) Зайти в любую папку === cd foldername1

6) Создать 5 файлов (3 txt, 2 json) === touch file1.txt file2.txt file3.txt file4.json file5.json

7) Создать 3 папки === mkdir foldername4 foldername5 foldername6

8. Вывести список содержимого папки = ls -la

9) + Открыть любой txt файл === vim file1.txt

10) + написать туда что-нибудь, любой текст === нажимаем i (insert) -> вводим необходимый текст

11) + сохранить и выйти. === escape -> : -> w (сохраняем) -> q (выходим)

12) Выйти из папки на уровень выше === cd ..

13) переместить любые 2 файла, которые вы создали, в любую другую папку. === mv foldername1/file1.txt file2.txt foldername2

14) скопировать любые 2 файла, которые вы создали, в любую другую папку. === cp foldername2/file1.txt file2.txt folsername1

15) Найти файл по имени === find . -name "file1.txt"

16) просмотреть содержимое в реальном времени === tail -f file1.txt

17) вывести несколько первых строк из текстового файла === head -2 file1.txt 

18) вывести несколько последних строк из текстового файла === tail -3 file1.txt

19) просмотреть содержимое длинного файла === cat file1.txt | less

20) вывести дату и время === date
================================================

1) Отправить http запрос на сервер. 
http://162.55.220.72:5005/terminal-hw-request
== curl http://162.55.220.72:5005/terminal-hw-request
== curl "http://162.55.220.72:5005/get_method?name=siarhei&age=30"

2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13.
== touch script == vim script == i                                            
#!/bin/bash

cd/Homeworks/foldername1
mkdir folder_{2..4}
cd folder_2
touch file_{1..3}.txt {4,5}.json
mkdir new_1 new_2 new_3
ls -la
mv {file_1,file_2}.txt ../folder_3
== esc => : => w => q
== chmod +x script
== ./script 