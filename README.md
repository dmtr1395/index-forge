# Index Forge: Google Indexing Telegram Bot

![Index Forge](assets/banner.jpg)

**[@IndexForgeBot](https://t.me/IndexForgeBot)**: a Telegram bot that checks your pages and submits them to Google for indexing. **$0.01 per link**, 10 links free to start.

[English](#english) · [Русский](#русский)

---

## English

### What it does

Send the bot your pages in any form:

- a list of links, one per line;
- a `.txt` file with links;
- one or more sitemap URLs;
- just a domain like `example.com`: the bot finds the sitemap and collects every page itself.

Before submitting, the bot **checks every page the way Googlebot sees it**:

| Check | Why it matters |
|---|---|
| 404, 4xx, 5xx errors | a broken page can't be indexed |
| Redirects | Google indexes the target, not the redirecting URL |
| `noindex` (meta and `X-Robots-Tag`) | the page explicitly asks not to be indexed |
| `canonical` pointing elsewhere | Google will index the other URL instead |
| Blocked in `robots.txt` | Googlebot isn't allowed to crawl it |

Pages that fail are filtered out and listed with the reason. **You don't pay for them.** The rest are submitted after you confirm. If a URL isn't accepted, its credit is refunded automatically.

### Pricing

- 1 link = 1 credit = **$0.01**
- No subscriptions, no bundles: top up any amount from **$5**
- Payment: **USDT (BEP20 or TRC20)**
- **10 free links** for every new user
- Referral program: invite friends and get **20%** of their top-ups in credits

### How to start

1. Open **[t.me/IndexForgeBot](https://t.me/IndexForgeBot)** and press **Start**.
2. Paste your links, a sitemap or a domain.
3. Check the price and press **Send**.

Indexing usually takes 1 to 3 days.

---

## Русский

### Что делает бот

Пришли боту страницы в любом виде:

- ссылки, по одной в строке;
- `.txt`-файл со ссылками;
- один или несколько адресов sitemap;
- просто домен, например `example.com`: бот сам найдёт sitemap и соберёт все страницы.

Перед отправкой бот **проверяет каждую страницу так, как её видит Googlebot**:

| Проверка | Зачем |
|---|---|
| Ошибки 404, 4xx, 5xx | битая страница не попадёт в индекс |
| Редиректы | Google индексирует конечный адрес, а не редирект |
| `noindex` (meta и `X-Robots-Tag`) | страница сама просит её не индексировать |
| `canonical` на другой адрес | Google проиндексирует другой URL |
| Закрыта в `robots.txt` | Googlebot туда не пускают |

Такие страницы отсеиваются, и бот показывает, что с каждой не так. **За них не платишь.** Остальные уходят на индексацию после подтверждения. Если ссылку не приняли, кредит возвращается автоматически.

### Цена

- 1 ссылка = 1 кредит = **$0.01**
- Без подписок и пакетов: пополнение на любую сумму от **$5**
- Оплата: **USDT (BEP20 или TRC20)**
- **10 ссылок бесплатно** каждому новому пользователю
- Реферальная программа: **20%** от пополнений приглашённых друзей кредитами

### Как начать

1. Открой **[t.me/IndexForgeBot](https://t.me/IndexForgeBot)** и нажми **Старт**.
2. Пришли ссылки, sitemap или домен.
3. Проверь цену и нажми **Отправить**.

Индексация обычно занимает 1–3 дня.

---

**Keywords:** google indexing, index pages in google, fast indexing, url indexer, sitemap indexing, seo tool, telegram bot, индексация сайта в google, ускорить индексацию, индексатор ссылок.
