Задание
На ветке dev удаленного репозитория появились новые изменения и ваша задача добавить их в свою ветку перед своими,
опишите порядок ваших действий.
1. Обновление локальной ветки dev:
 - git checkout dev
 - git pull origin dev
2. Переключение на ветку task_4:
 - git checkout task_4
3. Обновление вашей ветки task_4:
 - git merge dev
4. Разрешение конфликтов (если есть):
 - git add .                 
 - git merge --continue      
5. Фиксация изменений:
 - git commit -m "Merged changes from dev into task_4"
6. Отправка изменений в удаленный репозиторий:
 - git push origin task_4
