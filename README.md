# 🚀 AI-Presentation Generator for Rosatom

<div align="center">

**🤖 Интеллектуальный ассистент для создания инвестиционных презентаций**  
*Автоматизация подготовки презентаций из технической документации*

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104+-green.svg)](https://fastapi.tiangolo.com)
[![React](https://img.shields.io/badge/React-18+-61dafb.svg)](https://reactjs.org)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

</div>

---

## ✨ Возможности

| Функция | Описание |
|---------|-----------|
| **📄 Умный анализ** | Автоматическая обработка PDF, DOCX, PPTX документов |
| **💬 Интеллектуальный чат** | Диалог с AI-ассистентом для формирования структуры |
| **🎯 Адаптация контента** | Подбор стиля для ГИП, менеджеров, инвесторов, руководства |
| **🏢 Корпоративный дизайн** | Автоматическое оформление по стандартам Росатома |
| **⚡ Быстрая генерация** | Готовая презентация за 2-3 минуты |

---

## 🎥 Демонстрация

<div align="center">

*Интерфейс сервиса - профессиональный и интуитивно понятный*

</div>

---

## 🛠 Технологии

**Backend:**
- **Python 3.11+** - основной язык разработки
- **FastAPI** - современный асинхронный фреймворк
- **PostgreSQL** - хранение данных пользователей
- **Redis** - кэширование и WebSocket соединения
- **ChromaDB** - векторная база для семантического поиска

**AI/ML:**
- **RAG архитектура** - Retrieval-Augmented Generation
- **YandexGPT / GPT-4** - большие языковые модели
- **Sentence Transformers** - создание векторных представлений

**Frontend:**
- **React 18 + TypeScript** - типобезопасная разработка
- **Tailwind CSS** - современная стилизация
- **WebSocket** - реальное время в чате

---

## 🚀 Быстрый старт

### Предварительные требования
- Python 3.11+
- Docker и Docker Compose
- API ключ для LLM (YandexGPT/GPT-4)

### Установка и запуск

```bash
# 1. Клонирование репозитория
git clone https://github.com/your-username/ai-presentation-rosatom.git
cd ai-presentation-rosatom

# 2. Настройка окружения
cp .env.example .env
# Отредактируйте .env файл, добавив ваши API ключи

# 3. Запуск через Docker
docker-compose up --build

# 4. Откройте в браузере
open http://localhost:3000
