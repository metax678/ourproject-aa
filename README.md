# Market Perspective — Astro Landing Page

## Локальный запуск

```bash
npm install
npm run dev
```

Открой http://localhost:4321

## Деплой на Vercel

### Вариант 1 — через GitHub (рекомендуется)

1. Залей папку в новый репозиторий GitHub
2. Зайди на https://vercel.com → **Add New Project**
3. Выбери свой репозиторий
4. Vercel автоматически определит Astro — просто нажми **Deploy**

### Вариант 2 — через Vercel CLI

```bash
npm install -g vercel
vercel
```

## Структура проекта

```
market-perspective/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro     ← базовый HTML-шаблон
│   └── pages/
│       └── index.astro      ← главная страница
├── astro.config.mjs          ← конфиг Astro + Vercel adapter
├── package.json
└── tsconfig.json
```

## Изменить ссылку на Telegram

В файле `src/pages/index.astro` найди строку:

```js
const TG_LINK = 'https://t.me/+7-C1JkydIiA3NzEy';
```

И замени на свою ссылку.
