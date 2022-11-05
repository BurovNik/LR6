# LR6
Лабораторная работа №6

### Создание корневой папки LR6
### инициализация --global user.name user. email.
Рисунок №1

![](image/1.png)


Рисунок №2

![](image/2.png)
### Клонирование удаленного репозитория


Рисунок №3

![](image/3.png)
### Добавление файла с GitHub на лок репозиторий


Рисунок №4

![](image/4.png)

### История коммитов ветки b master.
Рисунок №5

![](image/5.png)
### переход на ветку branch1 и обзор веток

Рисунок №6

![](image/6.png)

### лог для ветки branch1
Рисунок №7

![](image/7.png)

### переход на ветку master и попытка слияния

Рисунок №8

![](image/8.png)

### Решение конфликта при помощи mergetool

Рисунок №9

![](image/9.png)

### Переход в редактор Vim. Изменение файла с помощью команды :diffoff
Рисунок №10

![](image/10.png)

### Результат работы в редакторе Vim
Рисунок №11

![](image/11.png)

### Результат слияния и появление файла add, который впоследствии был удален вручную из директории
Рисунок №12

![](image/12.png)

### Создание доп файлов
Рисунок №13

![](image/13.png)

### Добавление новых файлов через add и commit

Рисунок №14

![](image/14.png)

### Откат на один commit назад
Рисунок №15

![](image/15.png)

### Удаление ветки branch1
Рисунок №16

![](image/16.png)

### Создание новой ветки OTCHET
Рисунок №17

![](image/17.png)

### Создание отчета в файле Readme.md с использованием редактора VScode

Рисунок №18

![](image/18.png)

## ЛОГ КОМАНД
```
$ cd D:/LR6
$ git clone 
$ git pull
$ cd LR6
$ git log
$ git checkout branch1
$ git branch1 -l
$ git log
$ git checkout master
$ git merge branch1
$ git mergetool
$ git status
$ git add NewTest.txt
$ git commit -m 'get txt file'
$ git add .
$ git commit -m 'get docx file'
$ git reset --hard HEAD~1
$ git branch -d branch1
$ git branch -l
$ git checkout -b 'OTCHET'
$ git branch -l
````
