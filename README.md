# TXT
 1. Создать внешний репозиторий c названием TXT.
 
*New repository*

![image](https://user-images.githubusercontent.com/105368491/173555599-b7e8cd7f-0a36-4755-b215-eca81ee2696f.png)

*Name: TXT*

![image](https://user-images.githubusercontent.com/105368491/173555634-e44b12de-2af6-4424-aa9b-d16a0bf8b0e8.png)

*Public*

![image](https://user-images.githubusercontent.com/105368491/173555659-f063a041-83bd-4480-b3fc-76f491f2a87d.png)

*Check "Add a README file"*

![image](https://user-images.githubusercontent.com/105368491/173555691-74ed8ed5-b9d8-4720-b4a0-1383dbee21f9.png)

*Press "Create repository"*

![image](https://user-images.githubusercontent.com/105368491/173555716-4db82c1c-81ba-4ba9-a66c-f86e8734eb5a.png)
 
 2. Клонировать репозиторий TXT на локальный компьютер. 
 
 `git clone https://github.com/torysub/TXT.git`

 3. Внутри локального TXT создать файл “new.txt”. 
 
 `touch new.txt`

 4. Добавить файл под гит.
 
 `git add new.txt`

 5. Закоммитить файл. 
 
 `git commit -m "Added the new.txt"`

 6. Отправить файл на внешний GitHub репозиторий. 
 
 `git push`

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT. 
 
 `vim new.txt`
 
 ```
 ФИО: Субботина Виктория Александровна;
Возраст: 31;
Домашние животные: коты -1, собаки - 1;
Зарплата: 1000$.
```

*Нажать **ESC"** :wq **"Enter"***

 8. Отправить изменения на внешний репозиторий. 
 
 ```
 git commit -am "New informayion added"
 
 git push
 ```

 9. Создать файл preferences.txt 
 
 `touch preferences.txt`

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT. 
 
 `vim preferences.txt`
 
 ```
Любимый фильм - "Интерстеллар";
Любимый сериал - "Друзья";
Любимое блюдо - паста, картофельное пюре, шашлык, салат;
Любимое время года - лето;
Страна - Австралия.
```

*Нажать **ESC"** :wq **"Enter"***

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT 
 
 `vim skills.txt`
 
 ```
 Skills:
 1) basic testing theory (testing, bug reports, documentation, SDLC, STLC);
 2) HTTP (client-server architecture, HTTP methods of requests to the server, HTTP server response codes, HTTP request and Response structures);
 3) data exchange format": (JSON", XML);
 4) database (SQL, Redis, Postgres);
 5) API (Postman, JS, API autotests);
 6) sniffing (Charles, Fidler);
 7) DevTools (Google Chrome, FireFox);
 8) mobile testing (iOS, Android(;
 9) building applications (Android Studio, XCode);
 10) working in the terminal (GitBush, GitHub);
 11) load testing (Jmeter);
 12) methodology (SCRUM).
 ```

*Нажать **ESC"** :wq **"Enter"***

 12. Сделать коммит в одну строку. 
 
 `git add . && git commit -m "Added the preferences.txt and the skills.txt"`

 13. Отправить сразу 2 файла на внешний репозиторий. 
 
 `git push`

 14. На веб интерфейсе создать файл bug_report.txt. 
 
 *Add file*

![image](https://user-images.githubusercontent.com/105368491/173555915-8f462aad-47f3-44f8-a2d5-d8dea1dfbf1f.png)

*Create new file*

![image](https://user-images.githubusercontent.com/105368491/173555947-720903e6-24de-4d71-b396-eb96548c2589.png)

*Name: bug_report.txt*

![image](https://user-images.githubusercontent.com/105368491/173557937-d48de215-42d0-4c0a-ab7f-e387e4388fb6.png)
 
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 *Commit New File*
 
 ![image](https://user-images.githubusercontent.com/105368491/173556117-b3b02bf5-f1a1-4871-a9da-83f703dc5caf.png)

 18. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 
 *Choose bug_report.txt*
 
 ![image](https://user-images.githubusercontent.com/105368491/173556637-3664423c-6165-48ed-ae22-456dca56262b.png)
 
 *Edit this file*
 
 ![image](https://user-images.githubusercontent.com/105368491/173556402-3bbdee99-76ce-43d6-ba1f-9ccb6742f0e4.png)
 
  ```
  Bug-ID: 1
  Title: Поле ввода 'Введите номер телефона' не позволяет ввести цифры после нажатия на кнопу 'Войти по номеру телефона'
  Project: Сайт магазина 'Malina'
  STR: 
    1. Открыть страницу входа;
    2. Нажать на кнопку 'Войти по номеру телефона';
    3. Начать вводить цифры  от 0 до 9 в поле 'Введите номер телефона'.
  AR: Невозможно ввести цифры от 0 до 9  в поле ввода 'Введите номер телефона'
  ER: В поле 'Введите номер телефона' возможно внести 10 цифр номера телефона от 0 до 9
  Environment:
    OS : Windows 10 PRO 64-bit operating system, x64 processor
    Browser : Google Chrome Version 102.0.5005.63 (Official build), (64 bit)
  Severity: Major
  Priority: Medium
  Status: New
  Author: Виктория Субботина
  ```

 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 
 *Commit changes*
 
 ![image](https://user-images.githubusercontent.com/105368491/173556527-0bf7a11a-df4d-4b6d-a963-c1ddf141c6e6.png)

 21. Синхронизировать внешний и локальный репозиторий TXT 
 
 `git pull`
