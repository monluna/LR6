# LR6
Лабораторная работа №6
# Скриншоты консоли и сторонних программ
Настройка git.
![Настройка git](/imades/1.png)
Клонирование репозитория.
![Клонирование репозитория](/imades/2.png)
Добавление созданого файла.
![Добавление созданого файла](/imades/3.png)
История операций для ветки master.
![История операций](/imades/4.png)
История операций для ветки branch1.
![История операций](/imades/5.png)
Последние изменения в branch1.
![Последние изменения](/imades/6.png)
Последние изменения в master.
![Последние изменения](/imades/7.png)
Создание и решение конфликта.
![Конфликт](/imades/8.png)
Файл с конфликтом.
![Конфликт](/imades/блокнот1.png)
Файл буз конфликта.
![Конфликт решен](/imades/блокнот2.png)
Удаление побочной ветки в локальном и удаленном репозитории. 
![Удаление ветки](/imades/9.png)
Пять коммитов.
![Коммиты](/imades/10.png)
![Коммиты](/imades/11.png)
Откат коммитов.
![Откат](/imades/12.png)
Создание ветки для отчета.
![Ветка для отчета](/imades/13.png)
# Лог команд
git --version
git config --global user.name "4016 Барсукова А.И."
git config --global user.email nastina2706@mail.ru
cd desktop
git clone https://github.com/monluna/LR6
cd LR6
git pull
git reflog --all
git checkout branch1
git reflog --all
git log -p -1
git checkout master
git log -p -1
git merge branch1
git status
git add mergefile.txt
git commit -m "Конфликт решен"
git branch -d branch1
git push origin --delete branch1
git add temp.txt
git commit -m "Добавлен новый файл"
git add temp3.txt
git commit -m "Создан ещё один файл"
git add temp.txt
git commit -m "Добавлена запись в файл"
git status
git add .
git commit -m "Второй файл удален"
git add .
git commit -m "Первый файл удален"
git status
git reset --hard HEAD~5
git status
git branch report
git checkout report
git add .
git commit -m "Добавлены скриншоты"
git add README.md
git commit -m "Добавлены скриншоты работы"