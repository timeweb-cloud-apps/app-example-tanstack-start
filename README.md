![TanStack Start Logo](https://st.timeweb.com/cloud-static/apps-logo/tanstack.svg)

# TanStack Start

Пример приложения [TanStack Start](https://tanstack.com/start), которое можно развернуть в **Timeweb Cloud Apps** без настройки.

:tada: [Демо]

:rocket: [Создать свой Apps](https://timeweb.cloud/my/apps/create)

:books: [Документация Timeweb Cloud Apps](https://timeweb.cloud/docs/apps)

## Параметры деплоя

Приложение разворачивается как frontend: при сборке страницы пререндерятся в HTML (`prerender` в `vite.config.ts`).

| Параметр          | Значение         |
| ----------------- | ---------------- |
| Фреймворк         | TanStack Start   |
| Команда сборки    | `npm run build`  |
| Директория сборки | `dist/client`    |

Пример с серверным рендерингом — [app-example-tanstack-start-ssr](https://github.com/timeweb-cloud-apps/app-example-tanstack-start-ssr).

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
npm install

# запуск в дев режиме с отслеживанием изменений
npm run dev

# сборка для продакшн с минификацией
npm run build

# локальный просмотр собранной сборки
npm run preview
```
