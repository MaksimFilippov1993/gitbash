1) Посмотреть где я

pwd

2) Создать папку

mkdir

3) Зайти в папку

cd

4) Создать 3 папки

	mkdir folder1 folder2 folder3

5) Зайти в любую папку

	cd folder 1

6) Создать 5 файлов (3 txt, 2 json)

	touch file1.txt file2……..json

7) Создать 3 папки

	mkdir folder_1 folder_2 folder_3

8. Вывести список содержимого папки

	ls -la

9) + Открыть любой txt файл

	vim file1.txt

10) + написать туда что-нибудь, любой текст.

	написал

11) + сохранить и выйти.

	esc :wq

12) Выйти из папки на уровень выше

	cd -

13) переместить любые 2 файла, которые вы создали, в любую другую папку.

mv file1.txt file2.txt ./folder_3

14) скопировать любые 2 файла, которые вы создали, в любую другую папку.

	cp 1.json 2.json ./folder_2

15) Найти файл по имени

	 find . -name file2.txt

16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает.

	tail -f file1.txt

17) вывести несколько первых строк из текстового файла

 	head -n 2 file1.txt

18) вывести несколько последних строк из текстового файла

 tail -n 5 file1.txt


19) просмотреть содержимое длинного файла (команда less) изучите как она работает.

less file1.txt

20) вывести дату и время

	date

Задание *
1) Отправить http запрос на сервер.
$ curl "http://162.55.220.72:5005/terminal-hw-request"
$ curl "http://162.55.220.72:5005/get_method?name=Maksim&age=28"


2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13

#!/bin/bash
mkdir /script
cd ./script
mkdir folder_1 folder_2 folder_3
cd folder_2
touch 1.txt	2.txt 3.txt 4.json 5.json
mkdir f_1 f_2 f_3
ls -la
mv 2.txt 5.json ../folder_1

