 # TXT HW
 1) Создать внешний репозиторий c названием TXT: == открыть  `https://github.com`  
                                                 - залогиниться. Нажать кнопку New					
                                                 - в поле Repository name ввести TXT,выбрать Public и Add a README file.
                                                 - Нажать Create repository.

2) Клонировать репозиторий TXT на локальный компьютер: 
                                                   = Нажать Code, выбрать HTTPS, скопировать ссылку на репозиторий, в gitbash зайти в папку (где будет размещаться репозиторий).
                                                 git clone git@github.com:NastyaGarkushova/TXT.git
                                                   - в терминале перейти в папку TXT (cd TXT), в конце адреса расположения отображается main
                                                 

3) Внутри локального TXT создать файл “new.txt” : == touch new.txt
                                                  == git status  (отображается красным цветом)

4) Добавить файл под гит:                         == git add new.txt
                                                  == git status (отображается зеленым)

5) Закоммитить файл:                              == git commit -m "add new.txt" (файл с комментарием создан)

6) Отправить файл на внешний GitHub репозиторий:  = git push (файл успешно отправлен на github)

7) Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
                                                 = Заходим в vim new.txt
                                                  i - перейти в режим редактирования:
                                                Full name: Garkushova Anastasia Alexandrovna
                                                Age:30
                                                Pets: 0
                                                Desired Salary: 500$
                                               Сохранить и выйти из vim
                                               - esc - выйти из режима редактрования
                                               -:wq - записать изменения и выйти из vim.

8)  Отправить изменения на внешний репозиторий:  == git add new.txt
                                                 == git commit -m "modified new.txt"
                                                 == git push

9)  Создать файл preferences.txt: touch preferences.txt 

10) В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате TXT.
                                                     = Заходим в vim preferences.txt
                                                  i - перейти в режим редактирования:
                                                     - favourite movie: Good Will Hunting
                                                     - favourite TV series: Stranger Things
                                                     - favourite food: Asian cuisine
                                                     - favourite season: summer
                                                     - country you would like to visit: South Korea 
                                                     = esc -:wq
                                               
11) Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT: 
                                                 = cat > skills.txt 
                                                skills: 
- Software testing theory
-client-server architecture
- HTTP server request methods
- HTTP server response codes
- Structures of HTTP requests and responses 
- JSON,XML. Their structure
- Removing and reading logs from an external server
- Sniffing  http web traffic through Charles and Fiddler
- Dev Tools of web browsers (Google Chrome, FireFox)
- VPN (How it works, why we need it, how to use, tool options)
- Mobile testing
- Feature of iOS,Android, guidelines
- Build iOs applications on XCode
- Build Android applications on Android studio
- ADB management of android devices
- Proxy and VPN settings on iOs and Android
- Sniffing of mobile traffic through Charles and Fiddler on iOS and Android
- Command line (terminal) Linux (copy, create, view, move files on services without a graphical interface)
- Bash scripting basics,automation of routine tasks on server
- Access to remote server
- SQL basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)
- Postgres database (installation, configuration and using)
- Non-relational database Redis (installation, configuration and using)
- Load testing in Jmeter
- Scrum development methodology
- Python (Learning basics. Creating a client-server applications

    = Enter
    = Ctrl+С

12) Сделать коммит в одну строку:  == git add preferences.txt; git add  skills.txt
                                   == git commit -m "add preferences.txt; skills.txt 


13) Отправить сразу 2 файла на внешний репозиторий: 
                                              == git push

14) На веб интерфейсе создать файл bug_report.txt. : 
                                                   == Войти в репозиторий TXT
                                                   == Нажать кнопку Add file
                                                   == Выбрать строку Create new file. В поле Name ввести bug_report.txt
15)  Сделать Commit changes (сохранить) изменения на веб интерфейсе
                                                   == В самом конце нажать кнопку Commit new file

16)  На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT: 
                                                   == Открыть файл bug_report.txt. Выбрать edit file и ввести текст: 

    Summary: There is opportunity input viral code in field "Имя" of form
Descriprion: There is opportunity input viral code in field "Имя" of form. It is risky for security and business like lost profit.
Actual result: code input
Expected result: disable or error
Reproduced on: Chrome
Reproducibility: always
For more details see attachment: https://veraksoff.info
Steps to reproduce:    
	1: Open URL:https://veraksoff.biz/testlab/megaform.php
	2: Fill all fields
        3: input viral code in field "Имя" of form from site https://virusinfo.info/showthread.php?t=20594
        4: Click [Регистрация] button
Severity: Critical
Priority: Medium
17) Сделать Commit changes (сохранить) изменения на веб интерфейсе: 
                                                   == Нажать кнопку Commit changes

18) Синхронизировать внешний и локальный репозиторий TXT:
                                                   == git pull




# HW JSON
1) Создать внешний репозиторий c названием Json: == открыть  https://github.com  
                                                 - залогиниться. Нажать кнопку New					
                                                 - в поле Repository name ввести JSON,выбрать Public и Add a README file.
                                                 - Нажать Create repository.

2) Клонировать репозиторий JSON на локальный компьютер: = Нажать Code, выбрать HTTPS, скопировать ссылку на репозиторий, в gitbash зайти в папку (где будет размещаться репозиторий).
                                                   == git clone git@github.com:NastyaGarkushova/JSON.git
                                                   - в терминале перейти в папку JSON (cd JSON), в конце адреса расположения отображается main.


3) Внутри локального TXT создать файл “new.txt” : == touch new.json
                                                  == git status  (отображается красным цветом)

4) Добавить файл под гит:                         == git add new.json
                                                  == git status (отображается зеленым)

5) Закоммитить файл:                              == git commit -m "add new.json" (файл с комментарием создан)

6) Отправить файл на внешний GitHub репозиторий:  = git push (файл успешно отправлен на github)

7) Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
                                                 = Заходим в vim new.json
                                                  i - перейти в режим редактирования:
                                                {

	                                           "full_name": "Garkushova Anastasiya Alexandrovna",
	                                           "age": 30,
	                                           "pets": 0,
	                                           "desired_salary": "500$"   
                                          
                                                 }
                                              Сохранить и выйти из vim
                                               - esc - выйти из режима редактрования
                                               -:wq - записать изменения и выйти из vim.

8) Отправить изменения на внешний репозиторий:  == git add new.json
                                                 == git commit -m "modified new.json"
                                                 == git push

9)  Создать файл preferences.json: touch preferences.json

10) В файл preferences.json” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате TXT.
                                                     = Заходим в vim preferences.json
                                                  i - перейти в режим редактирования:
                                                     {
	                                                "favourite_movie": "Good Will Hunting",
	                                                "favourite_tv_series": "Stranger Things",
	                                                "favourite_food": "Asian cousine",
	                                                "favourite_season": "Summer",
	                                                "country_you_would_like_to_visit": "South Korea"

                                                      }

                                                     = esc -:wq


11)  Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON: 
                                                 = cat > skills.json
                                                skills: 
{
"skills":[
	"software testing theory",
	"client-server architecture",
	"HTTP Server Request Methods",
	"HTTP server Response codes",
	"Structures of HTTP requests and responses",
	"JSON, XML. Their structure",
	"Removing and reading logs from an external server",
	"Sniffing http web traffic through Charles and Fiddler",
	"Dev Tools of web browsers Google Chrome, FireFox",
	"VPN. How it works, why we need it, how to use, tool options",
	"Mobile testing",
	"Feature of iOS, Android, guidelines",
	"Build iOS applications on Xcode",
	"Build Android applications on Android Studio",
	"ADB management of android devices",
	"Proxy and VPN settings on iOS and Android",
	"Interception (sniffing) of mobile traffic through Charles and Fiddler on iOS and Android",
	"Command line (terminal) Linux copy, create, view, move files on servers without a graphical interface",
	"Bash scripting basics, automation of routine tasks on  server",
	"Access to remote servers",
	"SQL basics Create, Delete, Drop, Insert Into, Select, From, Where, Join",
	"Postgres database installation, configuration and using",
	"Non-relational database Redis installation, configuration and using",
	"Load testing in Jmeter",
	"Scrum development methodology",
	"Python. Learning  basics. Creating a client-server applications"
	]
}
                                                = Enter
                                                = Ctrl+С

12) Сделать коммит в одну строку: ==git add preferences.json; git add  skills.json
                                  == git commit -m "add preferences.json; skills.json


13) Отправить сразу 2 файла на внешний репозиторий: 
                                              == git push

14) На веб интерфейсе создать файл bug_report.json. : 
                                                   == Войти в репозиторий JSON
                                                   == Нажать кнопку Add file
                                                   == Выбрать строку Create new file. В поле Name ввести bug_report.json

15) Сделать Commit changes (сохранить) изменения на веб интерфейсе
                                                   == В самом конце нажать кнопку Commit new file.

16) На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON: 
                                                   == Открыть файл bug_report.json. Выбрать edit file и ввести текст: 

                                                   {
                                                     "Summary": "There is opportunity input viral code in field 'Имя' of form",
                                                      "Description": "There is opportunity input viral code in field 'Имя' of form. It is risky for security and business like lost profit",
                                                       "Actual_result": "code input",
                                                       "Expected_result": "disable or error",
                                                       "Reproduced_on": "Chrome",
                                                       "Reproducibility": "always",
                                                       "For_more_details_see_attachment": "https://veraksoff.info",
                                                        "Steps to reproduce": 
                                                   {
                                                       "Step_1": "Open URL:https://veraksoff.biz/testlab/megaform.php",
	                                               "Step_2": "Fill all fields",
                                                       "Step_3": "input viral code in field 'Имя' of form from site https://virusinfo.info/showthread.php?t=20594",
                                                       "Step_4": "Click [Регистрация] button",
                                                                                               }
                                                      "Severity": "Critical",
                                                      "Priority": "Medium"
                                                                                                         }
17) Сделать Commit changes (сохранить) изменения на веб интерфейсе: 
                                                   == Нажать кнопку Commit changes

18) Синхронизировать внешний и локальный репозиторий JSON:
                                                   == git pull





# HW XML
1) Создать внешний репозиторий c названием XML: == открыть  https://github.com  
                                                 - залогиниться. Нажать кнопку New					
                                                 - в поле Repository name ввести XML,выбрать Public и Add a README file.
                                                 - Нажать Create repository.
2) Клонировать репозиторий JSON на локальный компьютер: = Нажать Code, выбрать HTTPS, скопировать ссылку на репозиторий, в gitbash зайти в папку (где будет размещаться репозиторий).
                                                   == git clone git@github.com:NastyaGarkushova/XML.git
                                                   - в терминале перейти в папку XML (cd XML), в конце адреса расположения отображается main.
3) Внутри локального XML создать файл “new.xml” : == touch new.xml
                                                  == git status  (отображается красным цветом)

4) Добавить файл под гит:                         == git add new.xml
                                                  == git status  (отображается зеленым)

5) Закоммитить файл:                              == git commit -m "add new.xml" (файл с комментарием создан)

6) Отправить файл на внешний GitHub репозиторий:  = git push (файл успешно отправлен на github)

7) Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
                                                 = Заходим в vim new.xml
                                                  i - перейти в режим редактирования:
                                                         <aboutme>
                                                 <fullname>Garkushova Anastasiya Alexandrovna</fullname>
	                                         <age>30</age>
	                                         <pets>0</pets>
		                                 <desiredsalary>500$</desiredsalary>
                                                          </aboutme>
                                                  Сохранить и выйти из vim
                                               - esc - выйти из режима редактрования
                                               -:wq - записать изменения и выйти из vim.
8) Отправить изменения на внешний репозиторий:  == git add new.xml
                                                 == git commit -m "modified new.xml"
                                                 == git push

9)  Создать файл preferences.xml: touch preferences.xml	 
  
10) В файл preferences.xml” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате TXT.
                                                     = Заходим в vim preferences.xml
                                                  i - перейти в режим редактирования:
                                                           <mypreferences>
	                                                <movie>Good Will Hunting</favouritemovie>
	                                                <tvseries>Stranger Things</tvseries>
	                                                <food>Asian cousine</food>
	                                                <season>Summer</season>
	                                                <country>South Korea</country>
                                                              </mypreferences>
                                                                = esc -:wq
11) Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON: 
                                                 = cat > skills.xml

                                                    <skills>
                                   <one>software testing theory</one>
                                   <two>client-server architecture</two>
                                   <three>HTTP server request methods</three>
                                   <four>HTTP server Response codes</four>
                                   <five>Structures of HTTP requests and responses</five>
                                   <six>JSON, XML. Their structure</six>
                                   <seven>Removing and reading logs from an external server</seven>
                                   <eight>Sniffing http web traffic through Charles and Fiddler</eight>
                                   <nine>Dev Tools of web browsers Google Chrome, FireFox</nine>
                                   <ten>VPN. How it works, why we need it, how to use, tool options</ten>
                                   <eleven>Mobile testing</eleven>
                                   <twelve>Feature of iOS, Android, guidelines</twelve>
                                   <thirteen>Build iOS applications on Xcode</thirteen>
                                   <fourteen>Build Android applications on Android Studio</fourteen>
                                   <fifteen>ADB management of android devices</fifteen>
                                   <sixteen>Proxy and VPN settings on iOS and Android</sixteen>
                                   <seventeen>Interception (sniffing) of mobile traffic through Charles and Fiddler on iOS and Android</seventeen>
                                   <eighteen>Command line (terminal) Linux copy, create, view, move files on servers without a graphical interface</eighteen>
                                   <nineteen>Bash scripting basics, automation of routine tasks on  server</nineteen>
                                   <twenty>Access to remote servers</twenty>
                                   <twentyone>SQL basics Create, Delete, Drop, Insert Into, Select, From, Where, Join</twentyone>
                                   <twentytwo>Postgres database installation, configuration and using</twentytwo>
                                   <twentythree>Non-relational database Redis installation, configuration and using</twentythree>
                                   <twentyfour>Load testing in Jmeter</twentyfour>
                                  <twentyfive>Scrum development methodology</twentyfive>
                                   <twentysix>Python. Learning  basics. Creating a client-server applications</twentysix>
                                                                     </skills>
                                                                      = Enter
                                                                       = Ctrl+С

12) Сделать коммит в одну строку: == git add preferences.xml; git add  skills.xml
                                  == git commit -m "add preferences.xml; skills.xml 


13) Отправить сразу 2 файла на внешний репозиторий: 
                                                   == git push
14) На веб интерфейсе создать файл bug_report.xml. : 
                                                   == Войти в репозиторий XML
                                                   == Нажать кнопку Add file
                                                   == Выбрать строку Create new file. В поле Name ввести bug_report.xml
15) Сделать Commit changes (сохранить) изменения на веб интерфейсе
                                                   == В самом конце нажать кнопку Commit new file.
16) На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML: 
                                                   == Открыть файл bug_report.xml. Выбрать edit file и ввести текст: 

                                                              <Bugreport>
    
                                       <summary>there is opportunity input viral code in field 'Имя' of form</summary>
  
                                       <description>there is opportunity input viral code in field 'Имя' of form. It is risky for security and business like lost profit</description
   
                                       <actualResult>code input</actualResult>
    
                                       <expectedResult>disable or error</expectedResult>
   
                                       <reproducedOn>Chrome</reproducedOn>
  
                                       <reproducibility>>always</reproducibility>
  
                                       <attachment>>https://veraksoff.info</attachment>
   
                                               <Steps to reproduce>
     
                                       <one>open URL:https://veraksoff.biz/testlab/megaform.php</one>
 
                                       <two>fill all fields</two>
     
                                       <three>input viral code in field 'Имя' of form from site https://virusinfo.info/showthread.php?t=20594</three>
   
                                       <four>click [Регистрация] button</four>
        
                                               </Steps to reproduce>                                                 
                                       <severity>critical</severity>                                  
   
                                       <priority>medium</priority>
         
                                                             </Bugreport>

17) Сделать Commit changes (сохранить) изменения на веб интерфейсе: 
                                                   == Нажать кнопку Commit changes

18) Синхронизировать внешний и локальный репозиторий XML:
                                                   == git pull

	                            
