**GIT. HOMEWORK_1**
0. Аккаунт в GitHub
```
https://github.com/raskote
```
**JSON**  
1. Создать внешний репозиторий c названием JSON.
```
Repository created
```
2. Клонировать репозиторий JSON на локальный компьютер.
```
git clone git@github.com:raskote/JSON.git
```
3. Внутри локального JSON создать файл “new.json”.
```
cd JSON
touch new.json
```
4. Добавить файл под гит.
```
git add .
```
5. Закоммитить файл.
```
git commit -m ‘added new.json’
```
6. Отправить файл на внешний GitHub репозиторий.
```
git push 
```
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```
nano new.json
{
    “name” : “Bogdanov Mikhail Borisovich”,
    “age” : 32,
    “count of pets” : 1,
    “required payment” : 100000
}
```
8. Отправить изменения на внешний репозиторий.
```
git add .
git commit -m “change of new.json”
git push
```
9. Создать файл preferences.json
```
touch preferences.json
```
10.	В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```
nano preferences.json
{
    “favourite movie” : “the dark knight”,
    “favourite show” : “the friends”,
    “favourite food” : “kfc”,
    “favourite season of year” : “summer”,
    “country which I want to visit” : “Germany”
}
```
11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
```
touch skills.json
nano skills.json
{
	"skill_0" : "Базовая теория",
	"skill_1" : "Что такое клиент-серверная архитектура", 
	"skill_2" : "HTTP методы запросов на сервер", 
	"skill_3" : "Коды ответов HTTP сервера", 
	"skill_4" : "Структуры HTTP запросов и ответов",
	"skill_5" : "Что такое JSON, XML. Их структура",
	"skill_6" : "Тестирование API через Postman (JS, автотесты API)",
	"skill_7" : "Снятие и чтение логов с внешнего сервера",
	"skill_8" : "Снифинг http web трафика через Charles и Fiddler",
	"skill_9" : "Dev Tools веб браузеров (Google Chrome, FireFox)",
	"skill_10" : "VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)",
	"skill_11" : "Мобильное тестирование",
	"skill_12" : "Особенность iOS, Android, гайдлайны",
	"skill_13" : "Сборка iOS приложений на XCode",
	"skill_14" : "Сборка Android приложений на Android Studio",
	"skill_15" : "ADB (управление андройд девайсами)",
	"skill_16" : "Настройка прокси и vpn на iOS и Android",
	"skill_17" : "Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android",
	"skill_18" : "Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)",
	"skill_19" : "Основы bash скриптинг, автоматизация рутинных задач на сервере",
	"skill_20" : "Доступ к удалённым серверам",
	"skill_21" : "Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
	"skill_22" : "База данных Postgres (установка, настройка и использование)",
	"skill_23" : "Нереляционная база данных Redis (установка, настройка и использование)",
	"skill_24" : "Нагрузочное тестирование в Jmeter",
	"skill_25" : "Методология разработки Scrum",
	"skill_26" : "Python. (Изучение основ. Создание клиент серверного приложения)"
}
```
12. Отправить сразу 2 файла на внешний репозиторий.
```
git add .
git commit -m “added 2 json files”
git push
```
13. На веб интерфейсе создать файл bug_report.json.
```
add file - create new file
bug_report.json
```
14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
commit new file
```
15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
```
{
  "Title" : "Example",
  "Description" : "Example",
  "Preposition" : "Example",
  "Steps to reproduce" : "Example",
  "Expected result" : "Example",
  "Actual result" : "Example",
  "Attachments": "Example"
}
```
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
commit changes
```
17. Синхронизировать внешний и локальный репозиторий JSON
```
git pull
```
**XML**  
18. Создать внешний репозиторий c названием XML.
```
Repository created
```
19. Клонировать репозиторий XML на локальный компьютер.
```
git clone git@github.com:raskote/XML.git
```
20. Внутри локального XML создать файл “new.xml”.
```
touch new.xml
```
21. Добавить файл под гит.
```
git add . 
```
22. Закоммитить файл.
```
git commit -m “added new.xml”
```
23. Отправить файл на внешний GitHub репозиторий.
```
git push
```
24. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```
nano new.xml
<?xml version="1.0" standalone="yes" ?>
<NewDataSet>
<Table>
    <ФИО>Богданов Михаил Борисович</ФИО>
	<Возраст>32</Возраст>
	<Количество_животных>1</Количество_животных>
	<Желаемая_зарплата>100000</Желаемая_зарплата>
</Table>
```
25. Отправить изменения на внешний репозиторий.
```
git add .
git commit –m “change of new.xml”
git push
```
26. Создать файл preferences.xml
```
touch preferences.xml
```
27. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```
nano preferences.xml
<?xml version="1.0" standalone="yes" ?>
<NewDataSet>
<Table>
	<Любимый_фильм>Темный рыцарь</Любимый_фильм>
	<Любимый_сериал>Друзья</Любимый_сериал>
	<Любимая_еда>KFC</Любимая_еда>
	<Любимое_время_года>Лето</Любимое_время_года>
	<Страна_которую_я_хотел_бы_посетить>Германия<Страна_которую_я_хотел_бы_посетить>
</Table>
```
28. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```
touch skills.xml
nano skill.xml
<?xml version=>1.0> standalone=>yes> ?>
<NewDataSet>
<Table>
	<skill_0>Базовая теория</skill_0>
	<skill_1>Что такое клиент-серверная архитектура</skill_1>
	<skill_2>HTTP методы запросов на сервер</skill_2>
	<skill_3>Коды ответов HTTP сервера</skill_3>
	<skill_4>Структуры HTTP запросов и ответов</skill_4>
	<skill_5>Что такое JSON XML. Их структура</skill_5>
	<skill_6>Тестирование API через Postman (JS автотесты API)</skill_6>
	<skill_7>Снятие и чтение логов с внешнего сервера</skill_7>
	<skill_8>Снифинг http web трафика через Charles и Fiddler</skill_8>
	<skill_9>Dev Tools веб браузеров (Google Chrome FireFox)</skill_9>
	<skill_10>VPN. (Как работает зачем нужен как использовать варианты инструментов)</skill_10>
	<skill_11>Мобильное тестирование</skill_11>
	<skill_12>Особенность iOS Android гайдлайны</skill_12>
	<skill_13>Сборка iOS приложений на XCode</skill_13>
	<skill_14>Сборка Android приложений на Android Studio</skill_14>
	<skill_15>ADB (управление андройд девайсами)</skill_15>
	<skill_16>Настройка прокси и vpn на iOS и Android</skill_16>
	<skill_17>Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android</skill_17>
	<skill_18>Командная строка (terminal) Linux (копирование создание просмотр перемещение файлов на серверах без графического интерфейса)<skill_18>
	<skill_19>Основы bash скриптинг автоматизация рутинных задач на сервере</skill_19>
	<skill_20>Доступ к удалённым серверам</skill_20>
	<skill_21>Основы SQL (Create Delete Drop Insert Into Select From Where Join)</skill_21>
	<skill_22>База данных Postgres (установка настройка и использование)</skill_22>
	<skill_23>Нереляционная база данных Redis (установка настройка и использование)</skill_23>
	<skill_24>Нагрузочное тестирование в Jmeter</skill_24>
	<skill_25>Методология разработки Scrum</skill_25>
	<skill_26>Python. (Изучение основ. Создание клиент серверного приложения)</skill_26> 
</Table>
```
29. Сделать коммит в одну строку.
```
git add .
git commit -m “change of preferences.xml”
```
30. Отправить сразу 2 файла на внешний репозиторий.
```
git push
```
31. На веб интерфейсе создать файл bug_report.xml.
```
add file - create new file
```
32. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
commit new file
```
33. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```
<?xml version="1.0" standalone="yes" ?>
<NewDataSet>
<Table>
  <Title>Example</Title>>
  <Description>Example</Description>
  <Preposition>Example</Preposition>
  <Steps_to_reproduce>Example</Steps_to_reproduce>
  <Expected_result>Example</Expected_result>
  <Actual_result>Example</Actual_result>
  <Attachments>Example</Attachments>
</Table>
```
34. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
commit changes
```
35. Синхронизировать внешний и локальный репозиторий XML
```
git pull
```
**TXT**  
36. Создать внешний репозиторий c названием TXT.
```
Repository created
```
37. Клонировать репозиторий TXT на локальный компьютер.
```
git clone git@github.com:raskote/TXT.git
```
38. Внутри локального TXT создать файл “new.txt”.
```
touch new.txt
```
39. Добавить файл под гит.
```
git add .
```
40. Закоммитить файл.
```
git commit -m “added new.txt”
```
41. Отправить файл на внешний GitHub репозиторий.
```
git push
```
42. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
```
nano new.txt
- ФИО: Богданов Михаил Борисович
- Возраст: 32
- Количество животных: 1
- Желаемая_зарплата: 100000
```
43. Отправить изменения на внешний репозиторий.
```
git add .
git commit -m “change of new.txt”
git pull
```
44. Создать файл preferences.txt
```
touch preferences.txt
```
45. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```
nano preferences.txt
- Любимый фильм: Темный рыцарь
- Любимый сериал: Друзья
- Любимая еда: KFC
- Любимое время года: Лето
- Страна которую я хотел бы посетить: Германия
```
46. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
```
touch skills.txt
nano skills.txt
Список изучаемых навыков  на курсе:
- Базовая теория 
- Что такое клиент-серверная архитектура 
- HTTP методы запросов на сервер 
- Коды ответов HTTP сервера 
- Структуры HTTP запросов и ответов 
- Что такое JSON XML. Их структура 
- Тестирование API через Postman (JS автотесты API) 
- Снятие и чтение логов с внешнего сервера 
- Снифинг http web трафика через Charles и Fiddler 
- Dev Tools веб браузеров (Google Chrome FireFox) 
- VPN. (Как работает зачем нужен как использовать варианты инструментов) 
- Мобильное тестирование 
- Особенность iOS Android гайдлайны 
- Сборка iOS приложений на XCode 
- Сборка Android приложений на Android Studio 
- ADB (управление андройд девайсами) 
- Настройка прокси и vpn на iOS и Android 
- Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android 
- Командная строка (terminal) Linux (копирование создание просмотр перемещение файлов на серверах без графического интерфейса)<skill_18>
- Основы bash скриптинг автоматизация рутинных задач на сервере 
- Доступ к удалённым серверам 
- Основы SQL (Create Delete Drop Insert Into Select From Where Join) 
- База данных Postgres (установка настройка и использование) 
- Нереляционная база данных Redis (установка настройка и использование) 
- Нагрузочное тестирование в Jmeter 
- Методология разработки Scrum 
- Python. (Изучение основ. Создание клиент серверного приложения)
```
47. Сделать коммит в одну строку.
```
git add .
git commit -m “added 2 txt files”
```
48. Отправить сразу 2 файла на внешний репозиторий.
```
git push
```
49. На веб интерфейсе создать файл bug_report.txt
```
add file - create new file
```
50. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
commit new file
```
51. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
```
- Title: Example
- Description: Example
- Preposition: Example
- Steps to reproduce: Example
- Expected result: Example
- Actual result: Example
- Attachments: Example
```
52. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
```
Commit changes
```
53. Синхронизировать внешний и локальный репозиторий TXT
```
git pull
```