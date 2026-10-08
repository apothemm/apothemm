<p><img src="./assets/header.svg" alt="apothemm — инструменты для спокойной работы. Графит и серебро." width="100%" /></p>

Практические проекты на **C#, C++, Go, Rust, TypeScript и Python**. Развиваюсь в разработке инструментов для повседневной работы: локальная обработка, понятные команды, проверяемое поведение.

[Основной проект](#основной-проект) · [Утилиты](#утилиты) · [Desktop](#desktop) · [Технологии](#технологии)

## Основной проект

### [VaultTrail ↗](https://github.com/apothemm/vault-trail)

**Версии файлов, которым можно доверять после проверки.**

Локальное хранилище резервных снимков на C# / .NET. Несколько задач в одной системе:

- Параллельное копирование и SHA-256; дедупликация одинакового содержимого.
- История снимков и сравнение добавленных, удалённых и изменённых файлов.
- Проверка целостности и восстановление с предварительным просмотром.
- Блокировка хранилища, проверка путей и интеграционные тесты на Windows и Linux.

[Код и запуск](https://github.com/apothemm/vault-trail#запуск) · [Архитектура](https://github.com/apothemm/vault-trail/blob/main/docs/architecture.md) · [Проверки](https://github.com/apothemm/vault-trail/actions)

Также: **[DiffSignal](https://github.com/apothemm/diffsignal)** — self-hosted мониторинг изменений веб-страниц с историей, сравнением версий, веб-интерфейсом и REST API. `Python / FastAPI / SQLite / Docker`

## Утилиты

| Проект | Технология | Для чего |
| :-- | :-- | :-- |
| [LogWorkbench](https://github.com/apothemm/log-workbench) | C# / .NET | Поиск в логах, фильтры уровней, статистика и JSON-отчёт |
| [CsvScout](https://github.com/apothemm/csv-scout) | C++17 / CMake | Проверка CSV, многострочные поля, пустые значения и ширина строк |
| [LinkPulse](https://github.com/apothemm/link-pulse) | Go | Конкурентные HTTP-проверки, тайм-ауты, статусы и задержка |
| [HashLedger](https://github.com/apothemm/hash-ledger) | Rust | SHA-256-манифесты каталогов и проверка файлов после передачи |
| [RepoLens](https://github.com/apothemm/repo-lens) | TypeScript / Node.js | Инвентаризация репозитория: расширения, объём и крупнейшие файлы |
| [DupeRadar](https://github.com/apothemm/dupe-radar) | Python | Поиск одинаковых файлов по размеру и хешу; отчёт без удаления |

## Desktop

| Приложение | Возможности | Запуск |
| :-- | :-- | :-- |
| [WorkDesk](https://github.com/apothemm/workdesk) · C++ | Задачи, приоритеты, заметки и таймер | [Windows EXE](https://github.com/apothemm/workdesk/releases/latest) |
| [SystemScope](https://github.com/apothemm/systemscope) · C++ | CPU, RAM, поиск процессов, диски и отчёты | [Windows EXE](https://github.com/apothemm/systemscope/releases/latest) |
| [DiskLens](https://github.com/apothemm/disk-lens) · Python | Анализ папок и крупных файлов, экспорт CSV | [Windows EXE](https://github.com/apothemm/disk-lens/releases/latest) |
| [SnippetShelf](https://github.com/apothemm/snippet-shelf) · Python | Шаблоны текста, теги, поиск и переменные | [Windows EXE](https://github.com/apothemm/snippet-shelf/releases/latest) |
| [FocusHarbor](https://github.com/apothemm/focus-harbor) · Python | Фокус-сессии, перерывы и журнал | [Windows EXE](https://github.com/apothemm/focus-harbor/releases/latest) |
| [SortMate](https://github.com/apothemm/sortmate) · Python | План сортировки файлов и отмена перемещений | [Инструкция](https://github.com/apothemm/sortmate) |

Ещё: [ShareSafe](https://github.com/apothemm/sharesafe) — локальная маскировка секретов в тексте; [Windows First Aid](https://github.com/apothemm/windows-first-aid) — AI-skill с PowerShell-сборщиком диагностики.

## Технологии

<p>
<img src="./assets/dotnet.svg" alt="C# / .NET" height="28" />
<img src="./assets/cpp.svg" alt="C++17" height="28" />
<img src="./assets/go.svg" alt="Go" height="28" />
<img src="./assets/rust.svg" alt="Rust" height="28" />
<img src="./assets/typescript.svg" alt="TypeScript" height="28" />
<img src="./assets/python.svg" alt="Python" height="28" />
<img src="./assets/actions.svg" alt="GitHub Actions" height="28" />
</p>

В репозиториях есть инструкции запуска, тесты и автоматические проверки. Особенности и ограничения каждого инструмента описаны в README.

Интересуют **стажировки и junior-позиции** в разработке и автоматизации. Продолжаю изучать архитектуру, конкурентность, тестирование и работу с данными через практические проекты. Идеи и замечания — в Issues соответствующего репозитория.

---

<sub>Small tools. Thoughtful systems. Continuous learning.</sub>
