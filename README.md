# Linux
1) Посмотреть где я -----> pwd
2) Создать папку -----> mkdir mygit
3) Зайти в папку -----> cd mygit
4) Создать 3 папки -----> mkdir one two three
5) Зайти в любоую папку -----> cd two
6) Создать 5 файлов (3 txt, 2 json) -----> touch 1.txt 2.txt 3.txt 1.json 2.json
7) Создать 3 папки -----> mkdir apple cat dog
8) Вывести список содержимого папки -----> ls
9) Открыть любой txt файл -----> vim 3.txt
  + написать туда что-нибудь, любой текст -----> Привет!
  + сохранить и выйти -----> esc :wq 
  + выйти из папки на уровень выше -----> cd .. 
10) Переместить любые 2 файла, которые вы создали, в любую другую папку -----> two/1.json two/2.txt two/cat
11) Скопировать любые 2 файла, которые вы создали, в любую другую папку -----> cp two/1.txt two/2.json two/dog
12) Найти файл по имени -----> find . -name 1.txt
13) Просмотреть содержимое в реальном времени (команда grep) изучите как она работает -----> tail -f file1.txt
14) Вывести несколько первых строк из текстового файла -----> head -n 4 1.txt

        Hello!
        My name Veronika!
        I'm currently taking a course in testing, Linux commands.

15 ) Вывести несколько последних строк из текстового файла -----> tail -n 2 1.txt

      I'm currently taking a course in testing, Linux commands.
      When searching for files, grep is convenient to use to filter the output of the find command, as was shown at the beginning of the material. But if you need to find some file in the system by its name or part of the name (in this case, the mask * is used), then it is best to turn to find. It will display the exact location of the file you are looking for.

16) Просмотреть содержимое длинного файла (команда less) изучите как она работает -----> less 1.txt

17) Вывести дату и время -----> date
