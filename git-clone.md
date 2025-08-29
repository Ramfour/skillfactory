[< Вернуться к содержанию](readme.md)
## git clone
**git clone** создаёт копию существующего репозитория. Эта команда не только загружает все файлы проекта, но и всю историю изменений, а также настраивает соединение с исходным репозиторием для последующей синхронизации.

Для примера:

```bash
# Клонирование репозитория по HTTPS
git clone https://github.com/username/repository.git

# Клонирование в конкретную папку
git clone https://github.com/username/repository.git my-project

# Клонирование по SSH
git clone git@github.com:username/repository.git

# Клонирование определенной ветки
git clone -b development https://github.com/username/repository.git

# Клонирование только последних коммитов (неполная история)
git clone --depth 1 https://github.com/username/repository.git
```