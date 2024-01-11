# RobotMotorsControl

Проект создан с целю изучения системы контроля версий git. Проект содержит фаил talker1.py в нем написан код управления виртуальным роботом turtle, он управляет роботом двигая его по sin/cos траекториям.

## Описание работы с git

1. Создания репозитория RobotMotorsControl.

Можно использовать git init, но я создал репозиторий на github и клонировал его коммандой git clone https://github.com/AntonChe32/RobotMotorsControl.git

2. Генерируем ключи для ssh.

3. Добавляем открытый ключ через настройки на github

4. Удаляем origin командой **git remote remove origin**, т.к. нам нужен доступ по ssh

5. Добавляем origin командой **git remote add origin git@github.com:AntonChe32/RobotMotorsControl.git**
 
6. Добавление, фиксация и отправка на хостинг.

6.1 Создан фаил README.md.<br>
6.2 Фаил README.md отредактирован.<br>
6.3 Фаил добавлен в область наблюдения коммандой **git add README.md**<br>
6.4 Фаилы зафиксированы командой **git commit -m "first edit"**<br>
6.5 Файлы отправлены на хостинг командой **git push**<br>

7. Создаем новую ветку командой **git checkout -b "feature_branch_name"**
