# LR6
Лабораторная работа №6  
Цель лабораторной работы: изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.  
## Ход работы:  
### 1. Настройка клиент git  
Вводим имя пользователя - "4918 Пак А.В" и  email - parkartyom0202@gmail.com  
![шаг 1](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-1.png)  
### 2. Клонирование удалённого репозитория на компьютер  
клонируем репозиторий и переходим в директорию  
![шаг 2](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-2.png)  
### 3. Добавление файла через интерфейс GitHub  
Добавляем файл qwerty.txt через интерфейс GitHub. Подтягиваем изменения в локальный репозиторий.  
![шаг 3](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-3.png)   
### 4. Получение всей истории операций  
Получаем историю всех операций для каждой из веток.  
### 5. Получение последних изменениий  
Получаем историю последних двух операций для каждой из веток.  
![шаг 4 и 5](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-5.png)  
### 6. Слияние в ветку master  
Выполняем слияние ветки branch1 в ветку master, разрешив конфликт c помощью графического интерфейса git.  
![шаг 6](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-6.png)  
![шаг 6](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-6-1.png)
![шаг 6](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-6-2.png)  
![шаг 6](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-6-3.png)  
![шаг 6](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-6-4.png)  
### 7. Удаление побочной ветки  
Удаляем побочную ветку после успешного слияния.
![шаг 7](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-7.png)  
### 8. Фиксирование изменений  
Делаем изменения в файле polyalo.txt и зафиксируем их, оставляя комментарии два раза.  
![шаг 8](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-8.png)  
### 9. Откат коммита  
Делаем «хард» откат коммита.  
![шаг 9](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-9.png)  
### 10. Создание ветки  
Создаем ветку report для отчёта.   
![шаг10](https://github.com/PolyaLo/LR6/blob/report/скрин/12.png?raw=true )

## Логи команд:  
*  git config --global user.name "4918 Пак А.В"
* git config --global usre.email parkartyom0202@gmail.com
* git clone https://github.com/TripIeZ/LR6-1
* cd LR6   
  
  
/*Добавление файл qwerty.txt через интерфейс GitHub*/
  
* git pull  
* git log  
* git log -2  
* git checkout branch1  
* git checkout master  
* git merge branch1  
  
/*Устранение конфликта в git GUI*/
    
* git branch -d branch   
    
 /*изменение в файле qwerty.lo №1*/   
   
* git add qwerty.txt  
* git commit -m "changes №1"  
  

 /*изменение в файле qwerty.lo №2*/   
   
* git add qwerty.txt  
* git commit -m "changes №2"  
* git reset --hard @~2  
* git branch report
## История операций:  
![история операций](https://github.com/TripIeZ/LR6-1/blob/master/c%D0%BA%D1%80%D0%B8%D0%BD%D1%8B/%D1%81%D0%BA%D1%80%D0%B8%D0%BD-11.png)  
Вывод:я изучил базовые возможности системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.  
