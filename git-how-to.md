1) Открываем терминал
2) Проверяем на существование ключа: ls ~/.ssh
3) Генерация ключа: ssh=leygen -t ed25519 (формат ключа) -С "revilsane.timur@gmail.com(почта)"
4) eval "$(ssh-agent -s)"
5) ssh-add ~/.ssh/id_ed25519
6) Добавиь ключ на сайт через настройки, ssh
7) git clone (Дальше ssh c github репозитория)
 
 Теперь продолжаем