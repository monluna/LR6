# LR6
Лабораторная работа №6
# Скриншоты консоли и сторонних программ
Настройка git.<br>
![Настройка git](./images/скрин1.PNG)<br>
Клонирование репозитория.<br>
![Клонирование репозитория](./images/скрин2.PNG)<br>
Добавление созданого файла.<br>
![Добавление созданого файла](./images/скрин3.PNG)<br>
История операций для ветки master.<br>
![История операций](./images/скрин4.PNG)<br>
История операций для ветки branch1.<br>
![История операций](./images/скрин5.PNG)<br>
Последние изменения в branch1.<br>
![Последние изменения](./images/скрин6.PNG)<br>
Последние изменения в master.<br>
![Последние изменения](./images/скрин7.PNG)<br>
Создание и решение конфликта.<br>
![Конфликт](/images/скрин8.png)<br>
Файл с конфликтом.<br>
![Конфликт](/images/блокнот1.png)<br>
Файл буз конфликта.<br>
![Конфликт решен](./images/блокнот2.PNG)<br>
Удаление побочной ветки в локальном и удаленном репозитории.<br>
![Удаление ветки](./images/скрин9.PNG)<br>
Пять коммитов.<br>
![Коммиты](./images/скрин10.PNG)<br>
![Коммиты](./images/скрин11.PNG)<br>
Откат коммитов.<br>
![Откат](./images/скрин12.PNG)<br>
Создание ветки для отчета.<br>
![Ветка для отчета](./images/скрин13.PNG)<br>
# Лог команд
git --version<br>
git config --global user.name "4016 Барсукова А.И."<br>
git config --global user.email nastina2706@mail.ru<br>
cd desktop<br>
git clone https://github.com/monluna/LR6<br>
cd LR6<br>
git pull<br>
git reflog --all<br>
git checkout branch1<br>
git reflog --all<br>
git log -p -1<br>
git checkout master<br>
git log -p -1<br>
git merge branch1<br>
git status<br>
git add mergefile.txt<br>
git commit -m "Конфликт решен"<br>
git branch -d branch1<br>
git push origin --delete branch1<br>
git add temp.txt<br>
git commit -m "Добавлен новый файл"<br>
git add temp3.txt<br>
git commit -m "Создан ещё один файл"<br>
git add temp.txt<br>
git commit -m "Добавлена запись в файл"<br>
git status<br>
git add .<br>
git commit -m "Второй файл удален"<br>
git add .<br>
git commit -m "Первый файл удален"<br>
git status<br>
git reset --hard HEAD~5<br>
git status<br>
git branch report<br>
git checkout report<br>
git add .<br>
git commit -m "Добавлены скриншоты"<br>
git add README.md<br>
git commit -m "Добавлены скриншоты работы"<br>
git add README.md<br>
git commit -m "Добавлены лог команд"<br>
git log --pretty=format:"%h, %cd, %an, %s"<br>
# История операция
![История операций](./images/скрин14.PNG)