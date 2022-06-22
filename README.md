# XML
 21. Создать внешний репозиторий c названием XML.
Создается репозиторий в гитхаб.
=> respositories =>new
 22. Клонировать репозиторий XML на локальный компьютер.
git clone
 23. Внутри локального XML создать файл “new.xml”.
touch new.xml
 24. Добавить файл под гит.
git add new.xml
 25. Закоммитить файл.
commit –m “add new.xml”
 26. Отправить файл на внешний GitHub репозиторий.
git push
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
vim new.xml
для начала редактирования => i
<xml>
	<Name>"Anastasia Aleksandrovna"</full name>
	<Age>"20"</Age>
	<Number of pets>"1 cute kitty"</Number of pets>
	<Future desired salary>"100 million"</Future desired salary>
для выхода из редактирования => esc => :wq
 28. Отправить изменения на внешний репозиторий.
git add new.xml
 git commit –m “edited content”
 git push
 29. Создать файл preferences.xml
touch preferences.xml
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
vim preferences.xml
для начала редактирования => i
<xml>
	<Favorite Movie>"The Maid"</Favorite Movie>
	<Favorite series>"Killing Eve"</Favorite series>
	<Favorite Food>"Noodles"</Favorite Food>
	<Favorite season>"Spring and autumn"</Favorite season>
	<Country I want to go to>"France"</Country I want to go to>
для выхода из редактирования => esc => :wq
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
vim skills.xml
для начала редактирования => i
<xml>
	<Skills>"Basic theory. HTTP structure and methods. JSON, XML, their structure. API testing via Postman. Mobile testing. SQL basics." </Skills>
для выхода из редактирования => esc => :wq
32. Сделать коммит в одну строку.
git commit –m “new xml files”
 33. Отправить сразу 2 файла на внешний репозиторий.
git add .
git push
 34. На веб интерфейсе создать файл bug_report.xml.
Создаётся файл bug_report.xml в гитхабе.
add file=>create new file
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
сommit changes
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
В гитхабе меняется файл bug_report.xml.
=>Edit this file
<xml>
	<Summary>"Persistent sneezing"</Summary>
	<Project>"Nastya"</Project>
	<Component>"Nasopharynx"</Component>
	<Version>"1.20" </Version>
	<Severity>"S5 Trivial"</Severity>
	<Priority>"P3 Low"</Priority>
	<Status>"New"</Status>
	<Author>"Anastasia" </Author>
	<Assigned To>"Anastasia"</Assigned To>
	<Description>"The bug was found at home, this error was caused by allergies or dust, just take a deep breath and the error will repeat. </Description> 
	<Actual result>”sneezing” </Actual result>
	<Expected result>”no sneezing”</Expected result>
37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
сommit changes
 38. Синхронизировать внешний и локальный репозиторий XML
git pull (чтобы проверить все ли правильно синхронизировалось используется команда git fetch)
