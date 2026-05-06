| Действие                | Команда dnf                     | Команда apt            |
| ----------------------- | ------------------------------- | ---------------------- |
| Поиск пакета            | `dnf search`                    | `apt search`           |
| Установка пакета        | `dnf install`                   | `apt install`          |
| Удаление пакета         | `dnf remove`                    | `apt remove`           |
| Информация о пакете     | `dnf info`                      | `apt show`             |
| Список установленных    | `dnf list installed`            | `apt list --installed` |
| Поиск по файлу          | `dnf provides`                  | `apt-file search`      |
| Очистка кэша            | `dnf clean all`                 | `apt clean`            |
| Обновление всех пакетов | `dnf update`                    | `apt upgrade`          |
| Обновление индексов     | `(автоматически)`               | `apt update`           |
| Полное удаление         | `dnf remove` (конфиги остаются) | `apt purge             |
