# TXT
// Создать внешний репозиторий c названием TXT.

 Create a new repository

 // Клонировать репозиторий TXT на локальный компьютер.
 
 $ git clone git@github.com:yuliyaper/TXT.git

 // Внутри локального TXT создать файл “new.txt”.
 
 $ touch new_txt
 
 // Добавить файл под гит.
 
 $ git add .
 
 // Закоммитить файл.
 
 $ git commit -m" new_txt"
 
 // Отправить файл на внешний GitHub репозиторий.
 
 $ git push
 
 // Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество     
    домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
    
 vim new_txt
 
 нажать i
 
 Ф.И.О  Перевощикова Юлия Леонидовна
 
 Возраст 41
 
 Количество домашних животных 1
 
 Будущая желаемая зарплата 1000 $
 
 нажать esp : wq
	
 // Отправить изменения на внешний репозиторий.
 
 $ git commit -am "change 1 new_txt"
 
 $ git push
 
 // Создать файл preferences.txt

 $ touch preferences.txt
 
 // В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая 
    еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
    
 vim preferences.txt
 
 нажать i
 
 Любимый фильм - "Лед"
 
 Любимый сериал - "Мажор"
 
 Любимая еда - винегрет
 
 Любимое время года- лето
 
Страна,которую хотели бы посетить - Канада

 нажать esp : wq
 
 // Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 
 $touch skils.txt
 
 $ vim skils.txt
 
 нажать i
 
 Навыки:  
1. Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC
2. Что такое клиент серверная архитектура.
3. Методы запросов на сервер.
4. Ответы сервера.
5. Структуры запросов и ответов.
6. Что такое JSON, XML. Их структура.
7. Тестирование API.
8. Снятие и чтение логов.
9. Postman, Fidler.
10. VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)
11. Dev Tools веб браузеров (Google Chrome, FireFox).
12. Мобильное тестирование.
13. Особенность iOS, Android, гайдлайны.
14. Сборка iOS приложений на XCode
15. Сборка Android приложений на Android Studio
16. Перехват мобильного трафика (сниффинг) через Charles
17. Настройка прокси на iOS и Android.
18. Командная строка (terminal) Linux Ubuntu. Копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса. 
19. Простой bash скриптринг , автоматизация рутинных задач на сервере.
20. Доступ к удалённым серверам.
21. Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join
22. Git
23. Jmeter
24. Методология разработки Scrum
25. Python. Создание собственного клиент-серверного приложения.

  нажать esp : wq

 // cдеать коммит в одну строку.Отправить сразу 2 файла на внешний репозиторий.
 
  $ git add .
  
  $ git commit -m "2 files"
  
  $ git push
  
 // На веб интерфейсе создать файл bug_report.txt.
 
  Add file
  
  Create new file
  
  Commit new file
 
 // На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 
 Нажать на bug_report.txt
 
 Edit this file
 
  ID: 1 AP. 
  
  Title: При нажатии на кнопку «Отправить сообщение» в форме обратной связи сообщение не отправляется.
  
  Summary:При нажатии на кнопку «Отправить сообщение» в заполненной форме обратной связи ничего не происходит. Аналогичное поведение, если форма не заполнена.
  
  Precondition: Страница «Контакты».
  
  Steps To Reproduce: 1.Заполнить поля формы обратной связи 
                      2.Нажать на копку "Отправить сообщение"
                      
  Expected Result: Сообщение отправляется либо система сообщает о невозможности его отправки.
  
  Actual Result: Сообщение не отправляется, не появляется ошибка об отправке. После нажатия на кнопку ничего не происходит.
  
  Priority: Высокий.
  
  Severity: Критический.
  
  OS: Windows 10.
 
 // Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 Commit changes
 
 // Синхронизировать внешний и локальный репозиторий TXT
 
 git pull
