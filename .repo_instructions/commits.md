<!-- markdownlint-configure-file {"MD041": false} -->

## [2025-10-13 13:44 GMT+3]

### docs: Create README.md

Создан начальный `README.md` с названием репозитория `cd-factory-tools`.

---

## [2025-10-16 10:50 GMT+3]

### chore: workspace setup, formatting & linting, gitignore, normalize line endings via .gitattributes

Настроено базовое окружение разработки.
Добавлены `.editorconfig`, `.gitattributes`, `.gitignore`, `.pre-commit-config.yaml`, `.github/workflows/lint.yml`, `pyproject.toml`.
Настроены линтеры `black` и `ruff`, CI для pre-commit и форматирования.
Создан каталог `docs/` и базовый `README.md` с описанием инструментов и производственного потока.

---

## [2025-10-16 13:13 GMT+3]

### chore: directory structure

Созданы основные каталоги репозитория и структура под Python CLI-инструменты (`src/`, `lib/`, `tests/`, `deploy/`, `docs/`).

---

## [2025-10-16 13:47 GMT+3]

### docs: Определение структуры документации

Добавлены файлы `README.md`, `CONTRIBUTING.md`, `docs/architecture.md`, `docs/README.md`.
Определены правила ветвления и коммитов, структура документации и назначение проекта.
Описан производственный поток (прошивка, конфигурация, BIST).

---

## [2025-10-20 11:58 GMT+3]

### docs(repo_instructions): AI workflow and repo_notes

Добавлены `.repo_instructions/WORKFLOW.md`, `repo_notes.md` и шаблоны (`commit_template.md`, `session_log_template.md`, `task_comment_template.md`, `detour_template.md`).
Зафиксированы правила ведения логов сессий и коммитов, структура заметок и принципы фиксации архитектурных решений.
Добавлены репозиторные заметки: архитектура инструментов, конфигурирование узлов и диагностика (BIST).
