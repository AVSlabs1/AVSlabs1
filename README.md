# Alex Vikol

Software Engineer специализирующийся на backend-разработке (Python), инфраструктурной автоматизации и внедрении LLM/AI-пайплайнов в прикладные бизнес-процессы. Проектирую отказоустойчивые асинхронные микросервисы, распределенные парсеры с обходом WAF/антифрод-систем и автономных ИИ-агентов.

[Telegram](https://t.me/stxrsx) · [Email](mailto:avs.alexdev@gmail.com)

---

### Основные направления

* **LLM & AI Integration:** Разработка агентных пайплайнов, систем классификации и суммаризации на базе API (OpenAI, Claude, Gemini, DeepSeek). Проектирование RAG-архитектур, автоматизация обработки клиентских обращений и смысловой анализ неструктурированных данных.
* **Web Scraping & Reverse Engineering:** Сбор сложноструктурированных данных под защитой WAF и систем поведенческого анализа (Kasada, Cloudflare). Оптимизация пулов Playwright (управление контекстами, изоляция ресурсов, сжатие трафика), перехват внутренних API мобильных и веб-приложений.
* **Backend & Workflow Automation:** Асинхронные REST API, модульные сервисы на Clean Architecture, интеграция очередей и планировщиков. Автоматизация десктопных и серверных рутинных операций.
* **Интерфейсы доставки ценности:** Разработка защищенных multi-tenant Telegram-систем на aiogram 3.x с ролевым доступом, FSM и выгрузкой аналитических отчетов.

---

### Технологический стек

* **Языки и фреймворки:** Python 3.11+, AsyncIO, FastAPI, aiogram 3.x, Pydantic v2
* **Базы данных и ORM:** SQLAlchemy 2.0 (Async), PostgreSQL, SQLite (aiosqlite)
* **Сбор данных:** Playwright, HTTPX, BeautifulSoup4, Browser Process Pooling
* **AI & Инженерия данных:** LLM APIs, Prompt & Context Architecture, Structured Outputs, JSON-LD extraction
* **DevOps & Инфраструктура:** Docker, Docker Compose, Linux, Git, APScheduler

---
<div align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=AVSlabs1&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="GitHub Stats" height="150" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=AVSlabs1&theme=dark&hide_border=true" alt="GitHub Streak" height="150" />
</div>

### Проекты в портфолио

* **[ozon-competitor-tracker](https://github.com/AVSlabs1/ozon-competitor-tracker)**  
  Асинхронный B2B SaaS-сервис мониторинга цен и складских остатков Ozon.
  * Реализован stealth-скрапинг на базе долгоживущего пула Chromium с фильтрацией сетевого трафика.
  * Каскадная схема детекции цен (JSON-LD -> SSR State -> DOM-fallback).
  * Параллельная обработка очередей товаров через `asyncio.Semaphore` и SQL-вычисление интервалов опроса.
  * Мультитенантная архитектура по `chat_id`, привязка групповых рабочих чатов, генерация отчетов в `.xlsx`.

---

<div align="left">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AVSlabs1&layout=compact&theme=dark&hide_border=true" alt="Top Languages" />
</div>
