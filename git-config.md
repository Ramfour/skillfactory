## git config
git config позволяет настраивать параметры Git на компьютере, хранящиеся в текстовых файлах конфигурации.

Для примера:

```bash
# Установка имени пользователя (для всех репозиториев)
git config --global user.name "Ваше Имя"

# Установка email (для всех репозиториев)
git config --global user.email "your.email@example.com"

# Просмотр всех настроек
git config --list