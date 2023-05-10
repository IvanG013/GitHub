# | GIT | Homework_1
___
___

### JSON

1. Создать внешний репозиторий c названием JSON.

>New repository "JSON"

2. Клонировать репозиторий JSON на локальный компьютер.

>git clone https://github.com/IvanG013/JSON.git

>cd JSON

3. Внутри локального JSON создать файл “new.json”.

>cat > new.json

4. Добавить файл под гит.

>git add new.json

5. Закоммитить файл.

>git commit -m "new"

6. Отправить файл на внешний GitHub репозиторий.

>git push

7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

>cat >> new.json

```
{
    
"FullName": "Huriak Ivan Ihorevich",
   
"Age": 30,
    
"Pets": 1,
    
"future salary": 1000$

}

```

8. Отправить изменения на внешний репозиторий.

>git add .

>git commit -m "new.changes"

>git push

9. Создать файл preferences.json
     
>cat > preferences.json

```

{

"My favorite movie": "One Day",

"My favorite series": "Friends",

"My favorite food": "Deruny",

"My favorite season": "Summer",

"Country to travel in the future": "Portugal"

}

```

10. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

```

{
"Basic theory": "What is testing, bug reports,   documentation, types, SDLC, STLC",
"Client server": client-server architecture,
"Request methods to server": "HTTP",
"Structure": "JSON, XML",
"Dev Tools of web browsers": "Google Chrome, FireFox;
"Testing": "Mobile",
"ADB": "android device management",
"Setup": "proxy and vpn on iOS and Android",
"Interception (sniffing) of mobile traffic": "Charles and  Fiddler on iOS and Android",
"Basic bash scripting": "automating routine tasks on the server",
"Access": "to remote servers",
"SQL Basics": "Create, Delete, Drop, Insert Into, Select, From, Where, Join",
"Database": "Postgres, installation, configuration and use",
"Load_testing": "Jmeter",
"Development methodology": "Scrum",
"Python": "Learning the basics, creating a client-server  application",
"API testing": "Postman (JS, API autotests)",
"Removing and reading logs": from an external server
}

```

11. Отправить сразу 2 файла на внешний репозиторий.

   >git add .

   >git commit -m "v3"

   >git push

12. На веб интерфейсе создать файл bug_report.json.

>Add file

>Create new file

>Commit new file

13. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

>-edit this file

>в строке Commit changes пишем новый Commit

>Commit changes

14. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

>-edit this file

```
{
 
 "ID": 1,
 
 "Summary": "The menu title [Prof] cannot be clicked",
 
 "Version": "Windows 11 pro",
 "Steps": "Navigate to car.com", "Select  one of the licenses FCA, CYSEC", Select EN language, lick on the  menu section [Ways to trade], Click on the menu title [Professional Traders],
 
 "Actual result": "The menu title [Professional Traders] cannot be clicked",
 
 "Expected result": "The menu title [Professional Traders]  click is available",
 
 "Severity": "Minor",

 "Priority": "Low",
 
 "Attachments": "Screenshots"

}
```
>Commit changes

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

>в строке Commit changes пишем новый Commit;

>нажимаем Commit changes

16. Синхронизировать внешний и локальный репозиторий JSON 

>git pull

___
___

### XML

1. Создать внешний репозиторий c названием XML

>New repository "XML"

2. Клонировать репозиторий XML на локальный компьютер

>git clone https://github.com/IvanG013/XML.git

>cd XML

3. Внутри локального XML создать файл “new.xml”

cat > new.xml

4. Добавить файл под гит

>git add new.xml

5. Закоммитить файл

>git commit -m "v1"

6. Отправить файл на внешний GitHub репозиторий.

>git push

7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

>cat >> new.xml

```
<info>
<Fullname>Huriak Ivan Ihorevich</Fullname>
<Age>30</Age>
<Count_of_pets>1</Count_of_pets>
<Future_salary>1000$</Future_salary>
</info>

```
8. Отправить изменения на внешний репозиторий.

>git add .

>git commit -m "new.changes"

>git push

9. Создать файл preferences.xml

>cat > preferences.xml

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

>cat >> preferences.xml

```
<info>
<My favorite movie> One Day,
"My favorite series": "Friends",
"My favorite food": "Deruny",
"My favorite season": "Summer",
"Country to travel in the future": "Portugal"
</info>
```
11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

```
<Skills>
<Basic_theory>What is testing, bug reports, documentation, types, SDLC, STLC</Basic_theory>
<Client_server>client-server architecture</Client_server>
<Request_methods_to_server>HTTP<Request_methods_to_server>
<Structure>JSON, XML</Structures>
<Dev_Tools_of_web_browsers>Google Chrome, FireFox</Dev_Tools_of_web_browsers>
<Testing>Mobile</Testing>
<ADB>android device management</ADB>,
<Setup>proxy and vpn on iOS and Android</Setup>,
<Interception_(sniffing)_of_mobile_traffic>Charles and Fiddler on iOS and Android</Interception_(sniffing)_of_mobile_traffic>,
<Basic_bash_scripting>automating routine tasks on the server</Basic_bash_scripting>,
<Access>to remote servers</Access>,
<SQL_Basics>Create, Delete, Drop, Insert Into, Select, From, Where, Join</SQL_Basics>,
<Database>Postgres, installation, configuration and use</Database>,
<Load_testing>Jmeter</Load_testing>,
<Development_methodology>Scrum</Development_methodology>,
<Python>Learning the basics. Creating a client-server application</Python>,
<API_testing>via Postman (JS, API autotests)</API_testing>,
<Removing_and_reading_logs>from an external server<Removing_and_reading_logs>,
</Skills>
```
12. Сделать коммит в одну строку.

>git add .

>git commit -am "add one line"

13. Отправить сразу 2 файла на внешний репозиторий.

>git push

14. На веб интерфейсе создать файл bug_report.xml.

>Add file

>Create new file

>Commit new file

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

>-edit this file

>в строке Commit changes пишем новый Commit

>Commit changes

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

>-edit this file
```
<Bug_report>
<ID>1</ID>
<Summary>The menu title [Prof] cannot be clicked</Summary>
<Version>Windows 11 pro</Version>
<Steps>Navigate to car.com, Select  one of the licenses FCA, CYSEC, Select EN language, lick on the  menu section [Ways], Click on the menu title [Professional Tr]</Steps>
<Actual result>The menu title [Professional Tr] cannot be clicked</Actual result>
<Expected result>The menu title [Professional Tr]  click is available</Expected result>
<Severity>Minor</Severity>
<Priority>Low</Priority>
<Attachments>Screenshots</Attachments>
</Bug_report>
```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе

>Commit changes

18. Синхронизировать внешний и локальный репозиторий XML

>git pull

___
___

### TXT

1. Создать внешний репозиторий c названием TXT.

>New repository "TXT"

2. Клонировать репозиторий XML на локальный компьютер

>git clone https://github.com/IvanG013/TXT.git

>cd TXT

3. Внутри локального XML создать файл “new.xml”

cat > new.txt

4. Добавить файл под гит

>git add new.txt

5. Закоммитить файл

>git commit -m "v1"

6. Отправить файл на внешний GitHub репозиторий.

>git push

7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

>cat >> new.txt

```
Fullname - Huriak Ivan Ihorevich
Age - 30
Count of pets - 1
Future salary 1000$

```
8. Отправить изменения на внешний репозиторий.

>git add .

>git commit -m "new.changes"

>git push

9. Создать файл preferences.txt

>cat > preferences.txt

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

>cat >> preferences.xml

```
About me:
My favorite movie - One Day;
My favorite series - Friends;
My favorite food - Deruny;
My favorite season - Summer;
Country to travel in the future - Portugal.
```
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

```
 My skills:
-Basic_theory - What is testing, bug reports,   documentation, types, SDLC, STLC;
-Client_server - client-server architecture;
-Request_methods to server - HTTP;
-Structure - JSON, XML;
-Dev Tools of web browsers - Google Chrome, FireFox;
-Testing - Mobile;
-ADB - android device management;
-Setup proxy and vpn on iOS and Android;
-Interception (sniffing) of mobile traffic - Charles and  Fiddler on iOS and Android;
-Basic bash scripting - automating routine tasks on the server;
-Access to remote servers;
-SQL Basics - Create, Delete, Drop, Insert Into, Select, From, Where, Join;
-Database - Postgres, installation, configuration and use;
-Load_testing - Jmeter;
-Development methodology - Scrum;
-Python - Learning the basics. Creating a client-server  application;
-API testing - Postman (JS, API autotests);
-Removing and reading logs from an external server.

```
12. Сделать коммит в одну строку.

>git add .

>git commit -am "one line"

13. Отправить сразу 2 файла на внешний репозиторий.

>git push

14. На веб интерфейсе создать файл bug_report.xml.

>Add file

>Create new file

>Commit new file

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

>-edit this file

>в строке Commit changes пишем новый Commit

>Commit changes

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

>-edit this file
```
Bug_report:
ID: 1;
Summary: The menu title [Prof] cannot be clicked;
Version Windows: 11 pro;
Steps: 
1) Navigate to car.com, 
2) Select  one of the licenses FCA, CYSEC, 
3) Select EN language, lick on the  menu section [Ways], 
4) Click on the menu title [Professional Tr]
Actual result: The menu title [Professional Tr] cannot be clicked;
Expected result: The menu title [Professional Tr]  click is available;
Severity: Minor;
Priority: Low;
Attachments: Screenshots;

```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе

>Commit changes

18. Синхронизировать внешний и локальный репозиторий XML

>git pull
