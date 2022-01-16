# TXT
 1. Создать внешний репозиторий c названием TXT.
 GitHub > Repositories > New > TXT
 2. Клонировать репозиторий TXT на локальный компьютер.
 git clone
 3. Внутри локального TXT создать файл “new.txt”.
 cat > new.txt
 employeeID 1
 name Bill
 salary 56000
 married true
 4. Добавить файл под гит.
 git add new.txt
 5. Закоммитить файл.
 git commit -m "new.txt adding for the first time"
 6. Отправить файл на внешний GitHub репозиторий.
 git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 vim new.txt
 employeeID 1
 name Bill
 salary 56000
 married true

 employeeID 2
 name Olli
 age 27
 animals 1
 salary 1000000
 /save and exit - :wq
 8. Отправить изменения на внешний репозиторий.
 git commit -am "add my employee2 information"
 git push
 9. Создать файл preferences.txt
 touch preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
 vim preferences.txt
 fav_movie-"The_Irony_of_Fate",
 fav_serial-"Friends_EN",
 fav_food-vegetarian_dishes,
 fav_season-summer,
 fav_country-Iceland.
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 touch skills.txt
 vim skills.txt
 GitBash_Terminal
 GitHub
 API
 SQL
 Jmeter
 HTTPmethods
 JSON/XML
 Charles
 Fidler
 VPN
 iOS_with_X-code
 Android_Studio
 PostgresDB
 Redis
 Python
 12. Сделать коммит в одну строку.
 git commit -a
 13. Отправить сразу 2 файла на внешний репозиторий.
 git add .
 git commit -m "add both txt files with preferences and skills"
 git push
 14. На веб интерфейсе создать файл bug_report.txt.
 TXT > Add file > Create new file > TXT/bug_report.txt
 Bug report
        id: 1,
        title: "Chat - User cannot rename group conversation"
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 Comment for commit: add bug_report with bug report id information
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 Click bug_report.txt > edit 
 Bug report
        id: 1,
        title: "Chat - User cannot rename group conversation"
        Type:  Bug,
        Priority: Medium,
        Affects_Version: None,
        Component: None,
        Labels: None,
        Sprint: S22,
 Description
        Steps_to_reproduce
                  1: Log in,
                  2: Open chat dialog,
                  3: Click on the Setting button,
                  4: Add user,
                  5: Add user to a group conversation,
                  6: Try to rename this group conversation
        Expected_result: User can rename group conversation.
        Actual_result: Rename conversation button is disabled.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 Comment for commit: Update bug_report.txt
 18. Синхронизировать внешний и локальный репозиторий TXT
 git fetch - проверка обновлений на внешнем репозитории
 git pull - синхронизация
