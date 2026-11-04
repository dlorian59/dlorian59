# Library documentation / Документация библиотек

[← Back to profile README / Назад к README профиля](../README.md)

Start with the library README: switch EN/RU, follow its quick start, then open a runnable example or the versioned guide. Everything here is ordinary Markdown in the repositories.

Начните с README библиотеки: выберите EN/RU, выполните быстрый старт, затем откройте запускаемый пример или руководство нужной версии. Все материалы — обычный Markdown внутри репозиториев.

| Library / Библиотека | Start and try / Начать и попробовать | Versions / Версии | API reference / Справочник |
| --- | --- | --- | --- |
| [reactive-pipeline-kit](https://github.com/59Alex/reactive-pipeline-kit) | [README · EN/RU](https://github.com/59Alex/reactive-pipeline-kit/blob/main/README.md) · [Examples / Примеры](https://github.com/59Alex/reactive-pipeline-kit/tree/main/docs/0.3.0/examples) | [Select / Выбрать](https://github.com/59Alex/reactive-pipeline-kit/blob/main/docs/index.md) | [EN](https://github.com/59Alex/reactive-pipeline-kit/blob/main/docs/0.3.0/reference.en.md) · [RU](https://github.com/59Alex/reactive-pipeline-kit/blob/main/docs/0.3.0/reference.ru.md) |
| [file-streams](https://github.com/59Alex/file-streams) | [README · EN/RU](https://github.com/59Alex/file-streams/blob/main/README.md) · [Examples / Примеры](https://github.com/59Alex/file-streams/tree/main/examples/consumer) | [Select / Выбрать](https://github.com/59Alex/file-streams/blob/main/docs/index.md) | [EN](https://github.com/59Alex/file-streams/blob/main/docs/0.1.0/reference-en.md) · [RU](https://github.com/59Alex/file-streams/blob/main/docs/0.1.0/reference-ru.md) |
| [browser-media-cache](https://github.com/59Alex/browser-media-cache) | [README · EN/RU](https://github.com/59Alex/browser-media-cache/blob/main/README.md) · [Examples / Примеры](https://github.com/59Alex/browser-media-cache/tree/main/demo) | [Select / Выбрать](https://github.com/59Alex/browser-media-cache/blob/main/docs/index.md) | [EN](https://github.com/59Alex/browser-media-cache/blob/main/docs/0.1.0/reference.en.md) · [RU](https://github.com/59Alex/browser-media-cache/blob/main/docs/0.1.0/reference.ru.md) |
| [browser-sse-relay](https://github.com/59Alex/browser-sse-relay) | [README · EN/RU](https://github.com/59Alex/browser-sse-relay/blob/main/README.md) · [Examples / Примеры](https://github.com/59Alex/browser-sse-relay/tree/main/demo) | [Select / Выбрать](https://github.com/59Alex/browser-sse-relay/blob/main/docs/index.md) | [EN](https://github.com/59Alex/browser-sse-relay/blob/main/docs/v0.1.0/reference.en.md) · [RU](https://github.com/59Alex/browser-sse-relay/blob/main/docs/v0.1.0/reference.ru.md) |
| [pg-task-lease](https://github.com/59Alex/pg-task-lease) | [README · EN/RU](https://github.com/59Alex/pg-task-lease/blob/main/README.md) · [Examples / Примеры](https://github.com/59Alex/pg-task-lease/tree/main/docs/0.3.0/examples) | [Select / Выбрать](https://github.com/59Alex/pg-task-lease/blob/main/docs/index.md) | [EN](https://github.com/59Alex/pg-task-lease/blob/main/docs/0.3.0/reference.en.md) · [RU](https://github.com/59Alex/pg-task-lease/blob/main/docs/0.3.0/reference.ru.md) |
| [relational-paths](https://github.com/59Alex/relational-paths) | [README · EN/RU](https://github.com/59Alex/relational-paths/blob/main/README.md) · [Examples / Примеры](https://github.com/59Alex/relational-paths/tree/main/docs/0.3.0/examples) | [Select / Выбрать](https://github.com/59Alex/relational-paths/blob/main/docs/index.md) | [EN](https://github.com/59Alex/relational-paths/blob/main/docs/0.3.0/reference.en.md) · [RU](https://github.com/59Alex/relational-paths/blob/main/docs/0.3.0/reference.ru.md) |
| [model-change-set](https://github.com/59Alex/model-change-set) | [README · EN/RU](https://github.com/59Alex/model-change-set/blob/main/README.md) · [Examples / Примеры](https://github.com/59Alex/model-change-set/tree/main/docs/0.3.0/examples) | [Select / Выбрать](https://github.com/59Alex/model-change-set/blob/main/docs/index.md) | [EN](https://github.com/59Alex/model-change-set/blob/main/docs/0.3.0/reference.en.md) · [RU](https://github.com/59Alex/model-change-set/blob/main/docs/0.3.0/reference.ru.md) |


The guides explain a task from setup to result. References list the public API, defaults, lifecycle, errors and boundaries, with links to source examples. New integration repositories are local candidates until GitHub access is restored.

Руководства проводят от настройки до результата задачи. Справочники перечисляют публичный API, значения по умолчанию, жизненный цикл, ошибки и ограничения со ссылками на исходники примеров. Новые репозитории интеграций пока подготовлены локально: публикация ожидает восстановления GitHub.

## Spring Boot and React / Spring Boot и React

Use these adapters to connect the core libraries to application configuration and component lifecycles. Business handlers, schemas and authorization stay in your application.

Эти адаптеры подключают библиотеки к настройкам приложения и жизненному циклу компонентов. Бизнес-обработчики, схемы и правила доступа задаются в приложении.

| Core library / Библиотека | Spring Boot | React |
| --- | --- | --- |
| reactive-pipeline-kit | [Pipeline and AOP policies / Пайплайны и AOP-политики](https://github.com/59Alex/reactive-pipeline-spring-boot-starter) · [API EN](https://github.com/59Alex/reactive-pipeline-spring-boot-starter/blob/main/docs/0.1.0/reference.en.md) / [RU](https://github.com/59Alex/reactive-pipeline-spring-boot-starter/blob/main/docs/0.1.0/reference.ru.md) | — |
| file-streams | [Streaming backend / Потоковый сервер](https://github.com/59Alex/file-streams-spring-boot-starter) · [API EN](https://github.com/59Alex/file-streams-spring-boot-starter/blob/main/docs/0.1.0/reference-en.md) / [RU](https://github.com/59Alex/file-streams-spring-boot-starter/blob/main/docs/0.1.0/reference-ru.md) | [Upload and download / Загрузка и скачивание](https://github.com/59Alex/file-streams-react) · [API EN](https://github.com/59Alex/file-streams-react/blob/main/docs/0.1.0/reference.en.md) / [RU](https://github.com/59Alex/file-streams-react/blob/main/docs/0.1.0/reference.ru.md) |
| browser-media-cache | — | [Cached media / Медиа с кэшированием](https://github.com/59Alex/browser-media-cache-react) · [API EN](https://github.com/59Alex/browser-media-cache-react/blob/main/docs/0.1.0/reference.en.md) / [RU](https://github.com/59Alex/browser-media-cache-react/blob/main/docs/0.1.0/reference.ru.md) |
| browser-sse-relay | — | [Notifications and recovery / Уведомления и восстановление](https://github.com/59Alex/browser-sse-relay-react) · [API EN](https://github.com/59Alex/browser-sse-relay-react/blob/main/docs/v0.1.0/reference.en.md) / [RU](https://github.com/59Alex/browser-sse-relay-react/blob/main/docs/v0.1.0/reference.ru.md) |
| pg-task-lease | [Annotated workers / Обработчики по аннотации](https://github.com/59Alex/pg-task-lease-spring-boot-starter) · [API EN](https://github.com/59Alex/pg-task-lease-spring-boot-starter/blob/main/docs/0.1.0/reference.en.md) / [RU](https://github.com/59Alex/pg-task-lease-spring-boot-starter/blob/main/docs/0.1.0/reference.ru.md) | — |
| relational-paths | [Report query configuration / Настройка запросов отчёта](https://github.com/59Alex/relational-paths-spring-boot-starter) · [API EN](https://github.com/59Alex/relational-paths-spring-boot-starter/blob/main/docs/0.1.0/reference.en.md) / [RU](https://github.com/59Alex/relational-paths-spring-boot-starter/blob/main/docs/0.1.0/reference.ru.md) | — |

The README explains prerequisites, commands and expected output. Example links open source code; run it using those instructions. Java compatibility and language features are described alongside each release.

В README указаны требования, команды и ожидаемый результат. Ссылки на примеры открывают исходники; запускайте их по этим инструкциям. Совместимость Java и использованные возможности языка описаны рядом с каждой версией.

[← Back to profile README / Назад к README профиля](../README.md)
