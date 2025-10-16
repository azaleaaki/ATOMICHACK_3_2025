# 🎯 AI-Presentation Generator for Rosatom

> 🤖 Интеллектуальный ассистент для автоматического создания инвестиционных презентаций из технической документации

---

## 🎥 Демонстрация работы

[![Демо видео](https://img.youtube.com/vi/YOUR_VIDEO_ID/0.jpg)](https://www.youtube.com/watch?v=YOUR_VIDEO_ID)

---

## 🏗️ Архитектура решения

```mermaid
graph TD
    A[Пользователь] --> B[Загрузка файлов: PDF/DOCX/PPTX]
    B --> C[Извлечение текста и данных]
    C --> D[Векторизация и сохранение в ChromaDB]
    D --> E[Чат-интерфейс с RAG-поиском]
    E --> F[LLM YandexGPT/GPT-4]
    F --> G[Генерация структуры презентации]
    G --> H[Адаптация под аудиторию]
    H --> I[Сборка PPTX в шаблоне Росатома]
    I --> J[Скачивание презентации]
    
    style A fill:#e1f5fe
    style B fill:#f3e5f5
    style C fill:#e8f5e8
    style D fill:#fff3e0
    style E fill:#fce4ec
    style F fill:#e3f2fd
    style G fill:#f1f8e9
    style H fill:#fff8e1
    style I fill:#e0f2f1
    style J fill:#e8eaf6
