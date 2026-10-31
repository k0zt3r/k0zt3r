<div align="center">

# k0zt3r

**AppSec · pentest tooling · CTF · локальные LLM**

Пишу инструменты, которые экономят время на пентесте, и учу локальные модели делать полезное — без облаков.

</div>

---

### 🔧 Проекты

| | Что это | Стек |
|---|---|---|
| **[wordcraft-normokontrol](https://github.com/k0zt3r/wordcraft-normokontrol)** | Помощник по нормоконтролю ИрГУПС: титульник, рамки и штампы, содержание, список источников и генератор шифра работы. Оформляет DOCX через Wordcraft и выдаёт PDF с отчётом о проверке | Python, Tkinter, Wordcraft CLI, PyMuPDF |
| **[ad-report-intake](https://github.com/k0zt3r/ad-report-intake)** | Локальный модуль для подготовки контекста Active Directory из отчётов об ИС: извлекает признаки с источниками, позволяет проверить выводы и отдаёт JSON с вектором защитных мер для будущего агента | Python, HTML/JS, PyMuPDF |
| **[caido-plugins](https://github.com/k0zt3r/caido-plugins)** | Плагины для Caido: JS Analyzer Plus находит маршруты, API-эндпоинты и захардкоженные секреты в JavaScript (AST + regex), SQLmap Manager запускает sqlmap из Caido с очередью задач и пишет результаты в Findings | TypeScript, Caido SDK, Acorn |
| **[telegram-persona-llm](https://github.com/k0zt3r/telegram-persona-llm)** | Telegram-бот, который отвечает в личке твоим стилем. QLoRA-дообучение Qwen3-14B на своей переписке, маскирование лосса по репликам, экспорт в GGUF, эксперимент с RAG — и [подробный отчет](https://github.com/k0zt3r/telegram-persona-llm/blob/main/docs/REPORT.md) о том, что сработало, а что нет | Unsloth, Transformers, Ollama, python-telegram-bot |
| **[fstec-rag](https://github.com/k0zt3r/fstec-rag)** | Ответы по нормативке ИБ — приказы ФСТЭК, 149-ФЗ, 152-ФЗ — с цитатами источников | FastAPI, sentence-transformers, RAG |
| **[obsidian-rag-bot](https://github.com/k0zt3r/obsidian-rag-bot)** | Telegram-бот поверх своего Obsidian Vault: спрашиваешь — отвечает по заметкам | Flowise, Ollama, Docker |
| **[steam-enrich-scraper](https://github.com/k0zt3r/steam-enrich-scraper)** | Пайплайн скрапинг → обогащение → публикация: рукописные парсеры (BeautifulSoup), обогащение данными через Steam API и два взаимозаменяемых паблишера — REST-клиент и Selenium-автозаполнение формы с проверкой человеком | Python, BeautifulSoup, Selenium, requests |

### 🧭 Чем занимаюсь

- **Web AppSec** — анализ клиентского JavaScript, автоматизация рутины в прокси, SQL-инъекции
- **CTF** — участвую и помогаю новичкам втянуться
- **Локальные LLM** — RAG, агенты, дообучение (QLoRA) и запуск на обычном железе
- **Скрапинг и автоматизация** — рукописные парсеры, работа с REST API, Selenium
- **Linux, сети, железо** — от DevOps до ESP32

### 🛠 Инструменты

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Caido](https://img.shields.io/badge/Caido-1E1E2E)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4B8BBE)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?logo=ollama&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?logo=huggingface&logoColor=black)
