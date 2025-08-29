[< Вернуться к содержанию](readme.md)
## git remove add

На данный момент мы плавно переходим к *"Работе с удаленным репозиторием"*

**git remove add** — это команда для добавления ссылки на удалённый репозиторий в ваш локальный репозиторий. Она позволяет вам работать с несколькими удалёнными репозиториями и даёт им понятные имена для удобства.

Для примера:

```bash
# Добавить удалённый репозиторий с именем 'origin'
git remote add origin https://github.com/username/repository.git

# Добавить второй удалённый репозиторий (например, апстрим)
git remote add upstream https://github.com/original-author/repository.git

# Добавить репозиторий с использованием SSH
git remote add origin git@github.com:username/repository.git