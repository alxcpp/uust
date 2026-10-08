# Инструкция по публикации на GitHub

## Шаги для публикации репозитория:

1. Откройте GitHub в Microsoft Edge и войдите в свой аккаунт

2. Создайте новый репозиторий:
   - Нажмите кнопку "+" в правом верхнем углу
   - Выберите "New repository"
   - Название: `ugatu-events-catalog` (или любое другое на ваш выбор)
   - Описание: "Каталог мероприятий Уфимского университета науки и технологий"
   - Выберите "Public" или "Private"
   - НЕ инициализируйте репозиторий (не добавляйте README, .gitignore или лицензию)
   - Нажмите "Create repository"

3. После создания репозитория GitHub покажет инструкции. Выполните команды в PowerShell:

```powershell
cd "C:\Users\Alex\AppData\Local\Claude-3p\local-agent-mode-sessions\da43661b\00000000\fb8393b4\outputs"

# Замените YOUR_USERNAME на ваше имя пользователя GitHub
git remote add origin https://github.com/YOUR_USERNAME/ugatu-events-catalog.git
git branch -M main
git push -u origin main
```

4. После выполнения команд обновите страницу репозитория на GitHub

5. Для включения GitHub Pages (чтобы сайт был доступен онлайн):
   - Зайдите в Settings репозитория
   - Перейдите в раздел Pages (в боковом меню)
   - В Source выберите "Deploy from a branch"
   - Выберите ветку "main" и папку "/ (root)"
   - Нажмите Save
   - Сайт будет доступен по адресу: https://YOUR_USERNAME.github.io/ugatu-events-catalog/

## Расположение файлов

Файлы проекта находятся в папке:
C:\Users\Alex\AppData\Local\Claude-3p\local-agent-mode-sessions\da43661b\00000000\fb8393b4\outputs

Содержит:
- index.html - основной файл сайта
- README.md - описание проекта
- .git/ - Git-репозиторий (уже инициализирован и готов к публикации)
