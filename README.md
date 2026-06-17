# Git Practice: Большаков Юрий

Учебный проект для закрепления Git, GitHub и VS Code: README.md, .gitignore,
коммиты, ветки, merge, fetch, pull и разрешение конфликтов.

## Информация о студенте

| Поле            | Значение                                   |
|-----------------|--------------------------------------------|
| ФИО             | Большаков Юрий                             |
| Группа          | рпо23                                      |
| Дисциплина      | Git и GitHub                               |
| Дата выполнения | 17.06.2026                                 |
| Ссылка на GitHub| https://github.com/rpotopacademy-lang/git_practice_bolsakov_23 |

## Цель работы

Закрепить полный цикл работы с Git и GitHub через графический интерфейс VS Code.

## Выполненные этапы

1. Клонировал(а) шаблон проекта из GitHub.
2. Проверил(а)/инициализировал(а) Git-репозиторий.
3. Создал(а) файлы README.md, .gitignore, main.py, docs/notes.md.
4. Настроил(а) .gitignore (.env, venv/, __pycache__/, *.log не попадают в Git).
5. Сделал(а) несколько осмысленных коммитов через Source Control.
6. Опубликовал(а) репозиторий на GitHub через Publish Branch.
7. Создал(а) ветку feature/readme-update.
8. Внёс(ла) изменения в ветке и сделал(а) коммит.
9. Слил(а) ветку в main через Merge.
10. Выполнил(а) Fetch и Pull, увидел(а) разницу.
11. Создал(а) и разрешил(а) конфликт в README.md.
12. Оформил(а) README.md как отчёт со скриншотами.

## Использованные Git-действия

- Clone Repository
- Initialize Repository
- Stage Changes
- Commit
- Publish Branch
- Push / Sync Changes
- Fetch
- Pull
- Create Branch / Switch Branch
- Merge
- Resolve Conflict
- Git Graph

## Таблица Git-действий и их смысла

| Действие              | Где в VS Code                     | Смысл                                                   |
|-----------------------|-----------------------------------|---------------------------------------------------------|
| Clone Repository      | Command Palette → `Git: Clone`    | Копирует репозиторий с GitHub на компьютер              |
| Initialize Repository | Source Control                    | Создаёт локальный Git-репозиторий                       |
| Stage Changes         | Source Control, кнопка `+`         | Подготавливает файлы к коммиту                          |
| Commit                | Поле `Message` + кнопка `Commit`  | Сохраняет версию проекта в истории                      |
| Publish Branch        | Source Control                    | Публикует проект/ветку на GitHub                        |
| Push / Sync Changes   | Source Control                    | Отправляет и синхронизирует коммиты с GitHub            |
| Fetch                 | Source Control → `...` → `Fetch`  | Проверяет изменения на GitHub, не меняя локальные файлы |
| Pull                  | Source Control → `...` → `Pull`   | Загружает и применяет изменения с GitHub                |
| Create / Switch Branch| Панель снизу слева, Git Graph     | Создаёт и переключает ветки                             |
| Merge                 | Git Graph / Command Palette       | Объединяет изменения одной ветки с другой               |
| Resolve Conflict      | Редактор VS Code                  | Выбор или объединение конфликтующих изменений           |
| Git Graph             | Расширение Git Graph              | Показывает историю коммитов и веток                     |

## Разница между Fetch и Pull (впишите в отчёт)

> Fetch проверяет и загружает информацию о новых коммитах из GitHub, но **не меняет**
> мои рабочие файлы. Pull загружает изменения и **сразу применяет** их к текущей ветке.
> Я проверил(а) это: изменил(а) README.md на GitHub, сделал(а) Fetch (файлы не изменились),
> а затем Pull (изменения применились).

## Конфликт и его решение
> Я создал(а) конфликт в README.md: одна и та же строка была изменена на GitHub и локально.
> После Pull в файле появились маркеры конфликта. Я выбрал(а) итоговый вариант, удалил(а)
> служебные маркеры, добавил(а) файл в Stage, сделал(а) коммит решения конфликта
> и отправил(а) изменения на GitHub.


## Скриншоты выполнения работы
### 1. Созданный проект в VS Code
![01](screenshots/01_repository_created.png)

### 2. Инициализированный репозиторий
![02](screenshots/02_git_initialized.png)

### 3. Первый коммит
![03](screenshots/03_first_commit.png)

### 4. Репозиторий на GitHub
![04](screenshots/04_github_repository.png)

### 5. Созданная ветка
![05](screenshots/05_branch_created.png)

### 6. Результат merge
![06](screenshots/06_merge_completed.png)

### 7. Выполнение Fetch / Pull
![07](screenshots/07_fetch_or_pull.png)

### 8. Итоговая история в Git Graph
![08](screenshots/08_final_git_graph.png)


## Вывод 
я освоил базу гита 
