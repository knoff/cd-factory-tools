<!-- markdownlint-configure-file {"MD041": false} -->

## [2025-10-15]

**Начало:**    14:00 GMT+3
**Окончание:** 15:30 GMT+3

### Выполнено

- Создана структура репозитория `cd-factory-tools` для производственных и сервисных инструментов Coffee Digital.
- Определены ключевые модули CLI:
  - `flash` — прошивка контроллеров ESP32;
  - `provision` — конфигурирование узлов и запись параметров;
  - `bist` — базовое тестирование узлов после сборки.
- Настроено рабочее окружение: `.editorconfig`, `.gitattributes`, `.gitignore`, `pyproject.toml`, `.pre-commit-config.yaml`, `black`, `ruff`, `pre-commit`, GitHub Actions (`lint.yml`).
- Подготовлена документация (`README.md`, `CONTRIBUTING.md`, `docs/architecture.md`, `docs/README.md`) с описанием назначения и архитектуры.
- Добавлены `.repo_instructions/WORKFLOW.md`, `repo_notes.md` и шаблоны (`commit_template.md`, `session_log_template.md`, `task_comment_template.md`, `detour_template.md`).
- Зафиксированы репозиторные заметки (архитектура инструментов, конфигурирование узлов, диагностика).
- Проверены и приведены к единому виду pre-commit и форматирование markdown-шаблонов.

### Коммиты

- `docs: Create README.md`
- `chore: workspace setup, formatting & linting, gitignore, normalize line endings via .gitattributes`
- `chore: directory structure`
- `docs: Определение структуры документации`
- `docs(repo_instructions): AI workflow and repo_notes`

### Незавершённые задачи

- Реализация CLI-интерфейсов для `flash`, `provision` и `bist` с использованием `typer`.
- Интеграция `esptool` и библиотек для последовательной прошивки ESP32.
- Добавление модулей тестирования оборудования (моки сенсоров, клапанов, нагревателей).
- Разработка шаблонов конфигураций для массовой прошивки и тестирования.
- Интеграция отчётности о BIST в SaaS через Headunit.

### Следующие шаги

- Реализовать минимальный CLI `flash` и протестировать прошивку универсального firmware.
- Добавить `provision` с записью параметров MQTT и ID узла.
- Разработать `bist` с локальной валидацией и выводом отчёта.
- Настроить CI для автоматического теста CLI и проверок pre-commit.
- Подготовить шаблон Docker-контейнера для сервисного режима.
