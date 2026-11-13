# TanStack Start на Deno

Пример приложения [TanStack Start](https://tanstack.com/start) на [Deno](https://deno.com/).

## Параметры деплоя

Выберите рантайм **Deno**, фреймворк **TanStack Start** и тип приложения **frontend**. Для frontend будет опубликована статическая сборка.

| Параметр | Значение |
| --- | --- |
| Фреймворк | TanStack Start |
| Версия Deno | 2.7.14 |
| Тип приложения | `frontend` |
| Команда сборки | `deno task build` |
| Директория сборки | `dist/client` |

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
deno install --allow-scripts

# сборка для продакшн
deno task build
```
