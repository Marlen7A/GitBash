# GitBash
 ### __1. Посмотреть где я.__ 
 - *`pwd`*   
 ### __2. Создать папку.__ 
 - *`mkdir folder1`*
  ### __3. Зайти в папку.__ 
 - *`cd folder1`*
   ### __4. Создать 3 папки.__ 
 - *`mkdir folder1 folder2 folder3`*
   ### __5. Зайти в любую папку.__ 
 - *`cd`*
  ### __6. Создать 5 файлов.__ 
 - *`touch 1.json 2.txt 3.xml 1.doc 2.doc`*
 ### __7. Вывести список содержимого папки.__ 
 - *`ls`*
  ### __8. Открыть любой тхт файл.__ 
 - *`vim 1.txt`*
 ### __9. Написать туда любой текст__ 
 - *`i`-редактирование*
  ### __10. Сохранить и выйти__ 
 - *`esc`-выйти с режима редактирования*
  - *`:x`-сохранить изменения*
 ### __11. Выйти из папки на уровень выше__ 
 - *`cd ..`*
 ### __12. Переместить любые 2 файла, которые вы создали, в любую другую папку.__ 
 - *`mv folder1/{1.txt,1.json} folder2`*
 ### __13. Скопировать любые 2 файла, которые вы создали, в любую другую папку.__ 
 - *`cp folder1/{1.txt,1.json} folder2`*
 ### __14. Найти файл по имени.__ 
 - *`find -name 2.txt`*
 ### __15. Посмотреть содержимое в реальном времени (команда grep) изучить как она работает.__ 
  - *`tail -f 1.txt | grep 'слово поиска'*
   - *`tail -f dir_1/1.txt`* 
### __16. Вывести несколько первых строк из текстового файла.__ 
   - *`head -2 1.txt`*
### __17. Вывести несколько последних строк из текстового файла.__ 
 - *`tail -2 1.txt`* 
### __18. Посмотреть содержимое длинного файла (команда less) изучите как она работает.__ 
 - *`less 1.txt`* 
 - *`q`* - выход из режима просмотра 
 
### __19. Вывести дату и время.__ 
 - *`date`*

## Задание
### __1. Отправить http запрос на сервер. htpp//162.55.220.72:5005/terminal-hw-request__
 - *`curl htpp//162.55.220.72:5005/terminal-hw-request`*
  - *`curl http://162.55.220.72:5005/get_method?name=Marlen\&age=34`*
### __2. Написать скрипт который выполнит автоматически пункты 3,4,5,6,7,8,13__
 ```css
cat > script.sh << EOF
#!/bin/bash
pwd
mkdir dir_4
cd dir_4
mkdir dir_4_1 dir_4_2 dir_4_3
cd dir_4_3
touch 10.txt 11.txt 12.txt 10.json 11.json
mkdir folder_4_1 folder_4_2 folder_4_3
ls -la
mv 10.json 12.txt folder_4_1
```



