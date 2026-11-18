# Pavel Konchakov — Telegram bots, Mini Apps & automation

**[English](#english) · [Русский](#русский)**

Telegram: **[@amipicasso](https://t.me/amipicasso)** · LinkedIn: [pavel-konchakov](https://www.linkedin.com/in/pavel-konchakov) · Munich, Germany

---

## English

I build Telegram bots and Mini Apps, automations that connect your website, chats and spreadsheets, and small data & AI tools. I study Information Systems (Wirtschaftsinformatik) at TUM and work in English, Russian and German.

### What I can build for you

| | |
|---|---|
| **Telegram bots & Mini Apps** | Bots with buttons, mini apps inside Telegram, reminders, group bots, AI assistants |
| **Business automation** | Website form → Telegram card → Google Sheets as a simple CRM; notifications, statuses, reports |
| **Data & AI** | Collecting data from websites, text analysis with LLMs, sorting and summarising messages |
| **Landing pages** | Fast multilingual sites on Next.js + Tailwind, hosted on GitHub Pages |

### Cases

#### 1. Hockey league fan app — Telegram bot + Mini App
Fans of the Russian U21 hockey league (all 26 clubs) get the schedule, results, standings, match protocols and player leaders inside Telegram, plus match reminders and a daily mini-game. League data is collected from open sources and rebuilt automatically every hour with GitHub Actions.
- **Stack:** Python, aiogram 3, vanilla JS Mini App, GitHub Actions, GitHub Pages
- **Live:** [@rhl_u21_bot](https://t.me/rhl_u21_bot) · **Code:** [RHL-BOT](https://github.com/ArPicasso/RHL-BOT) (public part)

#### 2. Sales pipeline for a web studio — enquiries to Telegram + Google Sheets CRM
Every enquiry from the website's contact form arrives in the team's Telegram group as a card with buttons. One tap changes the status (testing, postponed, declined, partner) and the change is written to a Google Sheet that works as the CRM. A second module finds leads on Google Maps: local businesses with good ratings (4.3+, 50+ reviews) but no proper website — 12 cities in Georgia and 9 in Uzbekistan, 23 niches.
- **Stack:** Python, FastAPI, python-telegram-bot, Google Sheets API, Playwright, Render
- **Code:** [fikus-alert-bot](https://github.com/ArPicasso/fikus-alert-bot)

#### 3. Atlas — AI planner in Telegram (bot + Mini App)
You write to the chat as usual — "mattress 160, curtains for the bedroom, router; connect internet by 1 November" — and the bot sorts it into *Buy / To do / Discuss* using Claude. A shared group with a flatmate becomes a shared list; the Mini App shows checklists, who takes what, deadlines and prices. Every bot action can be undone. Runs on Telegram Serverless, covered by an end-to-end test suite.
- **Stack:** JavaScript, Telegram Serverless (tgcloud), Claude API, Mini App without a build step
- **Code:** [Planner](https://github.com/ArPicasso/Planner)

#### 4. Saturn — anonymous English-practice chat bot
A Telegram bot that connects strangers for anonymous conversations in English, with rules, XP, coins and an escalating block system for rule-breakers. A separate static help centre explains the rules and answers common questions.
- **Stack:** Python, Telegram Bot API, GitHub Pages
- **Live:** [@tgsaturnbot](https://t.me/tgsaturnbot) · **Help centre:** [arpicasso.github.io/lingobserver-help](https://arpicasso.github.io/lingobserver-help/) · bot code is private

#### 5. Customer review analysis
Collects bank customer reviews from two websites, scores the sentiment of each review with a locally hosted LLM and groups reviews into ten topics (TF-IDF + KMeans). The result is an HTML report with word clouds. Team project of four, Sirius.AI 2024.
- **Stack:** Python, pandas, scikit-learn, NLTK, Selenium, BeautifulSoup
- **Code:** [Sirius_AI_2024](https://github.com/ArPicasso/Sirius_AI_2024)

#### 6. Agency landing page (concept)
Bilingual (RU/EN) landing page for a small web studio: services, portfolio with filters, process, pricing, team map and contact form. Content is kept separate from layout, so texts and prices are easy to change.
- **Stack:** Next.js 15, React 19, TypeScript, Tailwind CSS, Framer Motion
- **Code:** [our-agency](https://github.com/ArPicasso/our-agency)

### How to start
Write me on Telegram **[@amipicasso](https://t.me/amipicasso)** with a few lines about the task. I'll come back with questions, a suggested approach and an estimate.

---

## Русский

Делаю Telegram-ботов и Mini Apps, автоматизацию (сайт → Telegram → Google Таблицы) и небольшие инструменты для данных и ИИ. Учусь на Wirtschaftsinformatik в TUM (Мюнхен), работаю на русском, английском и немецком.

### Что могу сделать

- **Telegram-боты и Mini Apps** — кнопки, напоминания, боты для групп, мини-приложения внутри Telegram, ИИ-ассистенты
- **Автоматизация бизнеса** — заявка с сайта → карточка в Telegram → Google Таблица как простая CRM; статусы, уведомления, отчёты
- **Данные и ИИ** — сбор данных с сайтов, анализ текстов через LLM, сортировка и выжимки сообщений
- **Лендинги** — быстрые многоязычные сайты на Next.js + Tailwind

### Кейсы

1. **Приложение для болельщиков хоккейной лиги РХЛ U21** — бот + Mini App: календарь, результаты, таблица, протоколы и лидеры для всех 26 клубов, напоминания о матчах. Данные обновляются автоматически каждый час. [@rhl_u21_bot](https://t.me/rhl_u21_bot) · [код](https://github.com/ArPicasso/RHL-BOT)
2. **Воронка продаж для веб-студии** — заявки с сайта приходят в Telegram карточками с кнопками, статусы пишутся в Google Таблицу (CRM). Плюс поиск клиентов в Google Maps: бизнесы с хорошим рейтингом, но без нормального сайта. [код](https://github.com/ArPicasso/fikus-alert-bot)
3. **Атлас — ИИ-планировщик в Telegram** — пишешь в чат «матрас 160, шторы, роутер», бот через Claude раскладывает по спискам «Купить / Дела / Обсудить», в Mini App — галочки, «Беру», сроки и цены. [код](https://github.com/ArPicasso/Planner)
4. **Saturn — анонимный чат для практики английского** — правила, XP, монеты, система блокировок, отдельный сайт-справка. [@tgsaturnbot](https://t.me/tgsaturnbot) · [справка](https://arpicasso.github.io/lingobserver-help/)
5. **Анализ отзывов клиентов банка** — парсинг двух сайтов, оценка тональности локальной LLM, 10 тем через TF-IDF + KMeans, HTML-отчёт. [код](https://github.com/ArPicasso/Sirius_AI_2024)
6. **Лендинг для агентства (концепт)** — RU/EN, Next.js 15, Tailwind, Framer Motion. [код](https://github.com/ArPicasso/our-agency)

### Как начать
Напишите в Telegram **[@amipicasso](https://t.me/amipicasso)** пару строк о задаче — отвечу вопросами, предложу решение и оценку по срокам и цене.
