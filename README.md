# GitPraktikWork
Практическая работа по Git
# Выполнение
1. Создал аккаунт указал имя и почту

  ![](/SceenPic/1.png)

2. Создал репозиторий на git.com

  ![](/SceenPic/2.png)

3. Создал через проводник папку для работы с Git
4. Создал локальный репозиторий
  
    ```
    git init
    ```

5. Создал пустой текстовый документ через проводник
6. Сформировал документ 5 абзацев
   
  ![](/SceenPic/3.png)
  
7. Посмотрел статус репозитория
   
    ```
    git status
    ```

  ![](/SceenPic/4.png)

8. Добавил файл в папку

   ```
   git add NewDoc.txt
   ```
   
  ![](/SceenPic/3.png)
  
9. Создал коммит

   ```
   git commit -m "Новый документ"
   ```
   
  ![](/SceenPic/3.png)

11. Посмотрел протокол коммитов

  ```
  git log
  ```

  ![](/SceenPic/5.png)
  
11. Посмотрел изменения относительно последнего коммита
    
  ![](/SceenPic/6.png)
  
12. Изменил файл и отменил изменения
   
  ![](/SceenPic/7.png)
  
  ```
  git restore NewDoc.txt
  ```

  ![](/SceenPic/8.png)
  
13. Посмотрел существующие ветки

      ```
      git branch
      ```
      
  ![](/SceenPic/9.png)

14. Создал новую ветку

    ```
    git branch NewBranch
    ```
    
  ![](/SceenPic/10.png)
    
15. Переключился на ветку

    ```
    git checkout NewBranch
    ```
    
  ![](/SceenPic/11.png)

16. Создал новую ветку и сразу переключился

    ```
    git checkout -b DoubleNewBranch
    ```
    
  ![](/SceenPic/12.png)
  
17. Удалил ветку

    ```
    git branch -d DoubleNewBranch
    ```
    
  ![](/SceenPic/13.png)

18. Добавил merge

    ```
    git merge main
    ```
    
  ![](/SceenPic/14.png)

19. Создал конфликт в файле

  ![](/SceenPic/15.png)

  ![](/SceenPic/16.png)

20. Посмотрел в каких файлах есть конфликты

    ```
    git status
    ```
    
  ![](/SceenPic/17.png)

21. Устранил конфликт оставив в документе толко запись Main
  
  ![](/SceenPic/18.png)
  
  ![](/SceenPic/19.png)
  
22. Переключился на коммит

    ```
    git checkout 6e59b34c71b833a57aefeedd57eecc1953108e17
    ```

23. Сделал ребазирование текущей ветки

    ```
    git rebase main
    ```
    
  ![](/SceenPic/20.png)

24. Удалил ветку

    ```
    git branch -d NewBranch
    ```

26. Отправил изменения из локального репозитория для указанной 
ветки в удаленный

    ```
    git remote add https://github.com/Cameruncam/GitPraktikWork.git
    ```

    ```
    git push origin main
    ```

27. Забрал изменения из репозитория, для которого
 были созданы удаленные ветки по умолчанию

    ```
    git pull origin main
    ```
    
    ![](/SceenPic/13а.png)
    
29. Забрал изменения удаленной ветки из репозитория основной ветки 
по умолчанию

    ```
    git pull origin NewBranch
    ```
    
30. Создать копию репозитория.

    ```
    git clone https://github.com/Cameruncam/GitPraktikWork.git
    ```
    
    ![](/SceenPic/21.png)
    
