# VitePress Shell

Каркас сайта базы знаний без контента.

## Запуск

1. Установите Node.js LTS (вместе с npm).
2. В каталоге `site` выполните:
   - `npm install`
   - `npm run docs:dev`

## Доступ для друга в одной сети (LAN)

- Запустите `npm run docs:dev:host`
- Узнайте ваш IP командой `ipconfig` (IPv4)
- Друг открывает `http://ВАШ_IP:5173`

## Сборка

- `npm run docs:build`
- `npm run docs:preview`

## Публичная ссылка через GitHub Pages

В репозитории GitHub откройте `Settings -> Pages` и выберите:
- `Build and deployment: Source = GitHub Actions`

После этого каждый `git push` в `main/master` автоматически публикует сайт.
