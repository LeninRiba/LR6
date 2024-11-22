# Лабораторная работа №6
## Система контроля версий 

**Цель лабораторной работы**: изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## 1. Создание форка
Создана копия в личное хранилище из https://github.com/Kurtyanik/LR6/
![Новый форк](./screens/screen2.jpg)

## 2. Установка Git
Установка

![Установщик Git](./screens/screen1.jpg)

## 3. Изменение имени и почты пользователя
Команда для изменения имени пользователя:

```bash
$ git config --global user.name "Группа 4317 Шахова А.Г."
```
Команда для изменения почты пользователя:

```bash
$ git config --global user.email "a.shakhova.gn@gmail.com"
```
![Изменение имени х почты](./screens/screen3.jpg)

## 4. Клонирование репозитория

```bash
$ git clone https://github.com/LeninRiba/LR6
```

## 5. Добавление нового файла
![Александр Гамильтон](./screens/screen4.jpg)


## 6. Добавление изменений в локальный репозиторий

```bash
$ git pull
```

## 7. Получение данных для каждой из веток

```bash
$ git log --all --oneline
```

*Результат работы команды*

![картинка 6](./screens/screen6.jpg)

## 8. Просмотр последних изменений

```bash
$ git log -1
```

*Результат работы команды*

![картинка 5](./screens/screen5.jpg)

## 9. Решение конфликта и слияние веток

```bash
$ git checkout master
$ git merge branch1
```
Решение конфликта путем замены содержимого файла mergefile.txt в ветке branch1

## 10. Удаление побочной ветки после слияния

```bash
$ git branch -d branch1
```
![картинка 7](./screens/screen7.jpg)

## 11. Сделать изменения и зафиксировать их, оставляя комментарии, несколько раз.
Создание файлов

![Heathers x Arcane](./screens/screen8.jpg)
![MAX VERSTAPPEN](./screens/screen9.jpg)

Комментарии к файлам

![картинка 10](./screens/screen10.jpg)

## 12. Откат коммита
Откат к предыдущему коммиту:

```bash
$ git revert 10e7b0c
```
![картинка 11](./screens/screen11.jpg)

## 12. Создание ветки для отчета

```bash
$ git checkout -b report
```

## 13. Получение истории операций в форматированном виде

```bash
$ git log --pretty=format:"%h %ad %an %s" --date=short
```
![картинка 12](./screens/screen12.jpg)

## 14. Лог команд

```bash
$ git config --global user.name 
$ git config --global user.email
$ git clone
$ git pull
$ git log --all --oneline
$ git log -1
$ git checkout master
$ git merge branch1
$ git branch -d branch1
$ git revert
$ git checkout -b report
$ git log --pretty=format:"%h %ad %an %s" --date=short
```
