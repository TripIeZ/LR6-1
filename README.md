# LR6
Лабораторная работа №6  
Цель лабораторной работы: изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.  
## Ход работы:  
### 1. Настройка клиент git  
Вводим имя пользователя - "4918 Лозовая П.Д." и и email - polina.1009@yandex.ru  
![шаг 1](https://github.com/PolyaLo/LR6/blob/report/скрин/1.png?raw=true)  
### 2. Клонирование удалённого репозитория на компьютер  
клонируем репозиторий и переходим в директорию  
![шаг 2](https://github.com/PolyaLo/LR6/blob/report/скрин/2.png?raw=true)  
### 3. Добавление файла через интерфейс GitHub  
Добавляем файл polyalo.txt через интерфейс GitHub. Подтягиваем изменения в локальный репозиторий.  
![шаг 3](https://github.com/PolyaLo/LR6/blob/report/скрин/3.png?raw=true)   
### 4. Получение всей истории операций  
Получаем историю всех операций для каждой из веток.  
### 5. Получение последних изменениий  
Получаем историю последних двух операций для каждой из веток.  
![шаг 4 и 5](https://github.com/PolyaLo/LR6/blob/report/скрин/4.png?raw=true)  
### 6. Слияние в ветку master  
Выполняем слияние ветки branch1 в ветку master, разрешив конфликт c помощью графического интерфейса git.  
![шаг 6](https://github.com/PolyaLo/LR6/blob/report/скрин/5.png?raw=true)  
![шаг 6](https://github.com/PolyaLo/LR6/blob/report/скрин/6.png?raw=true)  
![шаг 6](https://github.com/PolyaLo/LR6/blob/report/скрин/7.png?raw=true)  
![шаг 6](https://github.com/PolyaLo/LR6/blob/report/скрин/8.png?raw=true)  
### 7. Удаление побочной ветки  
Удаляем побочную ветку после успешного слияния.
![шаг 7](https://github.com/PolyaLo/LR6/blob/report/скрин/9.png?raw=true)  
### 8. Фиксирование изменений  
Делаем изменения в файле polyalo.txt и зафиксируем их, оставляя комментарии два раза.  
![шаг 8](https://github.com/PolyaLo/LR6/blob/report/скрин/10.png?raw=true)  
### 9. Откат коммита  
Делаем «хард» откат коммита.  
![шаг 9](https://github.com/PolyaLo/LR6/blob/report/скрин/11.png?raw=true)  
### 10. Создание ветки  
Создаем ветку report для отчёта.
![шаг10](https://github.com/PolyaLo/LR6/blob/report/скрин/12.png?raw=true)  
## Логи команд:  
*  git config --global user.name "4918 Лозовая П.Д."
* git config --global usre.email polina.1009@yandex.ru
* git clone https://github.com/PolyaLo/LR6
* cd LR6   
  
  
/*Добавление файл polyalo.txt через интерфейс GitHub*/
  
* git pull  
* git log  
* git log -2  
* git checkout branch1  
* git checkout master  
* git merge branch1  
  
/*Устранение конфликта в git GUI*/
    
* git branch -d branch   
    
 /*изменение в файле polyalo.lo №1*/   
   
* git add polyalo.txt  
* git commit -m "changes №1"  
  

 /*изменение в файле polyalo.lo №2*/   
   
* git add polyalo.txt  
* git commit -m "changes №2"  
* git reset --hard @~2  
* git branch report
## История операций:  

