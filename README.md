# TXT

1. Создать внешний репозиторий c названием TXT.

new
create repository

 2. Клонировать репозиторий TXT на локальный компьютер.

git clone https://github.com/OlgaNastTest/TXT.git

 3. Внутри локального TXT создать файл “new.txt”.

cd TXT
touch new.txt

 4. Добавить файл под гит.

git add new.txt

 5. Закоммитить файл.

git commit -m "add new.txt"

 6. Отправить файл на внешний GitHub репозиторий.

git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

cat >> new.txt
1. full name: Olga Nastsiushenka.
2. age: 32.
3. number of pets: 0.
4. future desired salary: 1000$

Ctr C

 8. Отправить изменения на внешний репозиторий.

git add new.txt
git commit -m "replace new.txt"
git push

 9. Создать файл preferences.txt

touch preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

cat >> preferences.txt
My preferences:

1. favorite moovies: 1+1;
2. favorite serial: The Big Bang Theory;
3. favorite food: Pasta with seafood;
4. favorite time of year: Summer;
5. country i want to visit: Italy

 Ctr C

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

cat > sklls.txt
1. The basics of testing - Types of testing/ SDLC/ STLC/Software development methodologies/ test design techniques;
2. Client-server architecture;
3. Documentation - Checklists / Bug_reports / Test-case / Requirements;
4. Terminal Linux;
5. Git,GitHub,GitBush;
6. Postman;
7. SQL;
8.Chrome_DevTools;
9.Mobile testing.

 Ctr C

 12. Сделать коммит в одну строку.

git add .
git commit -m "replace 2 new.txt"

 13. Отправить сразу 2 файла на внешний репозиторий.

git push

 14. На веб интерфейсе создать файл bug_report.txt.

Create new file
Edit new file: bug_report.txt

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Commit new file

 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.

Bug report structure:

1. summary;
2. project;
3. component;
4. version;
5. severity;
6. priority;
7. steps to reproduce;
8. actual result;
9. expected result;
10. additional information.

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

Commit changes

 18. Синхронизировать внешний и локальный репозиторий TXT

git pull
