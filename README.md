# Лабораторная работа №6
## Система контроля версий 

**Цель лабораторной работы**: изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## 1. Создание форка
Создана копия в личное хранилище из https://github.com/Kurtyanik/LR6/
[картинка 1]

## 2. Установка Git
Установка 
[картинка 2]

## 3. Изменение имени и почты пользователя
Команда для изменения имени пользователя:

```bash
$ git config --global user.name "Группа 4317 Червоненко А.В."
```
Команда для изменения почты пользователя:

```bash
$ git config --global user.email "doritos7431@gmail.com"
```
[картинка 3]

## 4. Клонирование репозитория

```bash
$ git clone https://github.com/lovandish/LR6
```

## 5. Добавление нового файла
[картинка 4]

## 6. Добавление изменений в локальный репозиторий

```bash
$ git pull
```

## 7. Получение данных для каждой из веток

```bash
$ git log --all –oneline
```

*Результат работы команды*

[картинка 6]

## 8. Просмотр последних изменений

```bash
$ git log -1
```

*Результат работы команды*

[картинка 5]

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
[картинка 7]

## 11. Сделать изменения и зафиксировать их, оставляя комментарии, несколько раз.
[картинка 8] [картинка 9] [картинка 10]

## 12. Откат коммита
Откат к предыдущему коммиту:

```bash
$ git revert 10e7b0c
```
[картинка 11] 
## 12. Создание ветки для отчета

```bash
$ git checkout -b report
```

## 13. Получение истории операций в форматированном виде

```bash
$ git log --pretty=format:"%h %ad %an %s" --date=short
```
[картинка 12]
## 14. История операций
Список истории операций:
+ 81fa03e 2024-10-23 lovandish Create CHEESECAKE

