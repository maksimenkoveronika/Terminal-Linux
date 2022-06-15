2) Написать скрипт который выполнит автоматически пункты: 

	-------> Создать файл            (touch myskript.sh)
	
	-------> Открыть файл            (cat >> myskript.sh)
	
		-------> Зайти в папку 		 (cd one)
		
		-------> Создать 3 папки         (mkdir 1 2 3)
		
		-------> Зайти в любоую папку    (cd 2)
		
		-------> Создать 5 файлов        (touch 1.txt 2.txt 3.txt 1.json 2.json)
		
		-------> Создать 3 папки         (mkdir food sun table)
		
		-------> Вывести сп. сод.папки   (ls -la)
		
		-------> Переместить из папки    (mv 2.txt 1.json ../3)
		

touch myskript.sh

cat >> myskript.sh

	#!/bin/bash
	
	cd one
	
	mkdir 1 2 3
	
	cd 2
	
	touch 1.txt 2.txt 3.txt 1.json 2.json
	
	mkdir food sun table
	
	ls -la
	
	mv 2.txt 1.json ../3
	
		Запустить скрипт sh myskript.sh
