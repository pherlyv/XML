# XML

1. Создать внешний репозиторий c названием XML.
    * залогиниться на `https://github.com`.
    * нажать кнопку `New`.
    * в поле `Repository name` ввести XML, выбрать Public и Add a Readme file.
2. Клонировать репозиторий XML на локальный компьютер.
    * нажать `Code`, выбрать `https`, скопировать ссылку.
    * в `Gitbash` зайти в папку, в которой будет репозитороий (мой пример) `cd git_group_27`.
    * написать команду `git clone https://github.com/pherlyve/XML.git`.
    * зайти в папку XML `cd XML`.
3. Внутри локального XML создать файл “new.xml”.
    * команда `touch new.xml`.
4. Добавить файл под гит.
    * команда `git add new.xml`.
5. Закоммитить файл.
    * команда `git commit -m "file new.xml"`.
6. Отправить файл на внешний GitHub репозиторий.
    * команда `git push`.
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
    * команда `vim new.xml`.
    * нажать `I`.
```xml
<aboutme>
	<lastName>Redko</lastName>
	<firstName>Tima</firstName>
	<middleName>Dmitrievich</middleName>
	<age>24</age>
	<pets>
		<cat>0</cat>
		<dog>0</dog>
	</pets>
	<salary>300k/nanosec</salary>
</aboutme>
```
   * нажать `Ecs`.
   * написать `:wq`.
8. Отправить изменения на внешний репозиторий.
    * команда `git add new.xml`.
    * команда `git commit -m "updated file new.xml"`.
    * команда `git push`.
9. Создать файл preferences.xml
    * команда `touch preferences.xml`.
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
    * команда `vim preferences.xml`.
    * нажать `I`.
```xml
<preferences>
	<favoriteMovie>Blade Runner 2049</favoriteMovie>
	<favoriteSeries>South Park</favoriteSeries>
	<favoriteFood>Curd casserole</favoriteFood>
	<favoriteSeason>Autumn</favoriteSeason>
	<visiteCountry>Iseland</visiteCountry>
</preferences>
```
   * нажать `Ecs`.
   * написать `:wq`.
11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
    * создать файл `touch skills.xml`.
    * зайти для редактирования `vim skills.xml` и нажать `I`.
```xml
<skills>
	<One>Basic theory</One>
	<Two>Client-server architecture</Two>
	<Three>HTTP method of request to the server</Three>
	<Four>HTTP server response codes</Four>
	<Five>Structures of HTTP requests and responses</Five>
	<Six>What is JSON, XML. Their structure</Six>
	<Seven>API testing via Postman JS, API autotests</Seven>
	<Eight>Removing and reading logs from an external server</Eight>
	<Nine>Sniffing http web traffic through Charles and Fiddler</Nine>
	<Ten>Dev Tools of web browsers (Google Chrome, FireFox)</Ten>
	<Eleven>VPN. How it works, why you need it, how to use it, tool options</Eleven>
	<Twelve>Mobile testing</Twelve>
	<Thirteen>Feature of iOS, Android, guidelines</Thirteen>
	<Fourteen>Build iOS apps on Xcode</Fourteen>
	<Fifteen>Build Android apps on Android Studio</Fifteen>
	<Sixteen>ADB (android device management)</Sixteen>
	<Seventeen>Setting up proxy and vpn on iOS and Android</Seventeen>
	<Eighteen>Interception (sniffing) of mobile traffic via Charles and Fiddler on iOS and Android</Eighteen>
	<Nineteen>Command line (terminal) (copying, creating, viewing, moving files on servers without a graphical interface)</Nineteen>
	<Twenty>Basics of bash scripting, automation of routine tasks on the server</Twenty>
	<TwentyOne>Access to remote servers</TwentyOne>
	<TwentyTwo>Basics of SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)</TwentyTwo>
	<TwentyThree>Postgres database (installation, configuration and use)</TwentyThree>
	<TwentyFour>Non-relational database Redis (installation, configuration and use)</TwentyFour>
	<TwentyFive>Load testing in Jmeter</TwentyFive>
	<TwentySix>Scrum development methodology</TwentySix>
	<TwentySeven>Python. (Learning the basics. Building a client-server application)</TwentySeven>
</skills>
```
   * нажать `Ecs`.
   * написать `:wq`.
12. Сделать коммит в одну строку.
   * команада `git add . && git commit -m "preferences.json | skills.json`.
13. Отправить сразу 2 файла на внешний репозиторий.
    * команда `git add . ; git push`.
14. На веб интерфейсе создать файл bug_report.xml.
    * на github зайти в XML репозиторий.
    * нажать кнопку `Add file`.
    * нажать `Create new file` в поле ввода написать `bug_report.xml`.
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    * нажать `Commit new file`.
16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```xml
<BugReport>
	<Heading>An error in the word Правила ЫРГИ</Heading>
        <StepsToReproduce>
        <One>Login to the server using Login: Test, Password: Test</One>
        <Two>Click button Соглашение</Two>
        <Three>Find button 'Правила ЫРГИ'</Three>
        </StepsToReproduce>
  	<ExpectedResult>The text will be correct 'Правила ИГРЫ'</ExpectedResult>
  	<ActualResult>The text with an error 'Правила ЫРГИ'</ActualResult>
  	<ReproducedOn>Win 10</ReproducedOn>
  	<Severity>Minor</Severity>
  	<Priority>Low</Priority>
</BugReport>
```
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
    * нажать кнопку `Commit changes`.
18. Синхронизировать внешний и локальный репозиторий XML.
    * команда `git pull`.
