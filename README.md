# Th3ProxyTools

> [English version](README_EN.md)

Плагин для [exteraGram](https://exteragram.app/) — расширенный менеджер прокси.

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![exteraGram](https://img.shields.io/badge/exteraGram-plugin-6C3FE0)
![Platform](https://img.shields.io/badge/platform-Android-3DDC84?logo=android&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

## Возможности

- **Массовый пинг** — проверка всех прокси одной кнопкой с live-обновлением статусов
- **Нативный / TCP / HTTP** — три режима проверки на выбор
- **Флаги стран** — автоматическое определение геолокации и провайдера (ip-api.com)
- **Импорт/Экспорт** — импорт из буфера обмена, экспорт в Избранное
- **Сортировка по пингу** — одной кнопкой
- **Live UI** — статусы обновляются каждую секунду во время проверки

## Стек

- [exteraGram Plugin API](https://plugins.exteragram.app/) — платформа плагинов
- `ConnectionsManager` — нативный пинг прокси
- `ip-api.com` — batch-геолокация и ISP
- `SharedConfig` — управление списком прокси Telegram

## Установка

1. Скачайте `Th3ProxyTools.plugin`
2. Отправьте файл себе в Избранное в exteraGram
3. Нажмите на файл → «Установить плагин»

## Настройки плагина

| Параметр | Описание |
|---|---|
| Режим пинга | Нативный / TCP / HTTP (SOCKS) |
| URL (HTTP) | URL для HTTP-проверки через SOCKS |
| Флаги стран | Показывать флаг и провайдер |
| Кнопки | Пинг все / Сортировка / Импорт / Экспорт |

## Структура

```
Th3ProxyTools/
├── Th3ProxyTools.plugin   # Файл плагина
├── README.md              # Документация (RU)
├── README_EN.md           # Документация (EN)
└── LICENSE                # MIT
```

## Автор

[@th3_nek1t](https://t.me/th3_nek1t)

## Лицензия

MIT © 2026 Th3Nekit
