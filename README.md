# Проект парсинга pep

Парсер собирает данные c https://docs.python.org/3/.

Ключи:

* whats-new - Собирает ссылка на change log'и версий Python'a.
* latest-versions - Собирает ссылки на версии Python'a.
* download - Скачивает pdf документацию на Python.
* pep - Собирает статусы всех pep'ов и подсчитывает их количество. 


* -o, --output [pretty, file] - Выдает информацию файлом или в консоль(по-умолчанию).
* -c, --clear-cache - Очищает кеш уже посещенных страниц.

# Технологии

* Python3
* Beautifulsoup4
