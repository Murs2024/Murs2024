# 👋 Привет! Я Ольга

Юрист-разработчик (Legal Tech) и промпт-инженер. Разрабатываю и внедряю AI-решения для юридических и бизнес-процессов компаний.

**Мой фокус** — практические инструменты с измеримым эффектом:
- ✨ +30% к конверсии лидов
- ⚡ до 50% экономии времени команды
- 🚀 сокращение рутины и ускорение внутренних процессов

---

## 💼 Чем могу помочь бизнесу

- 🤖 Автоматизация юридических и операционных процессов с AI
- 🤖 Разработка Telegram-ботов и AI-ассистентов под конкретную задачу
- 🔍 RAG-решения по внутренним регламентам и документам
- 🔗 Интеграция LLM/API в действующие процессы компании
- 💬 Проектирование промптов и контроль качества AI-ответов

---

## ⭐ Ключевые проекты


### 🎯 LegalGenius
**Задача:** Ускорить анализ договоров и судебных актов  
**Решение:** Telegram-система на базе RAG (15+ кодексов), разбор рисков с ссылками на нормы права  
**Результат:** По оценке RAGAS: Faithfulness 0.83 и Context Precision 1.0 (средний балл 0.915, уровень "отличное качество")  
**Стек:** Python, LangChain, RAG, Telegram API, YandexGPT  
**Статус:** ✨ Активный проект  
**Ссылки:** [Презентация](https://drive.google.com/file/d/1A_XWDiC602fsAl4HWDowsrlFuS0mSND8/view?usp=sharing) | [📖 Документация](https://github.com/Murs2024/LegalGenius-docs#readme)

---


### 🎯 «Юристы Севера»
**Задача:** Повысить входящую конверсию и разгрузить команду  
**Решение:** Разработка и запуск коммерческого Telegram-бота  
**Результат:** +30% к конверсии лидов, до 50% экономии времени сотрудников  
**Стек:** Python, SaleBot, Telegram API, CRM-интеграция  
**Статус:** ✨ Активный проект  
**Ссылки:** Кейс и демо по запросу

---


### 🎯 RAG-ассистент по регламентам и правовым документам
**Задача:** Ускорить поиск и анализ норм во внутренней базе документов  
**Решение:** AI-инструмент с retrieval и релевантной выдачей  
**Результат:** Внедрена проверка качества через RAGAS (Faithfulness + Context Precision), ответы выдаются с источниками  
**Стек:** Python, LangChain, RAG, SQL, API  
**Статус:** ✨ Активный проект  
**Ссылки:** [GitHub](https://github.com/Murs2024/RAG-reglament) | [Release v1.0](https://github.com/Murs2024/RAG-reglament/releases/tag/v1.0)

---


### 🎯 DocuBot
**Задача:** Автоматизировать подготовку типовых юридических документов  
**Решение:** Интеллектуальный генератор документов с шаблонами и проверками  
**Результат:** Доступен бесплатный тест-драйв бота для проверки сценариев  
**Стек:** Python, Telegram API, ChatGPT, шаблонизация  
**Статус:** ✨ Активный проект  
**Ссылки:** [Презентация](https://drive.google.com/file/d/1H-bfHi59BMWlh43QXfev7K2_tNnk58jO/view) | [Тест-драйв в Telegram (@docsdemo_bot)](https://t.me/docsdemo_bot)

---


### 🎯 Luma2025 — Персональный AI-планировщик (Telegram + MAX + Google Calendar)
**Задача:** Автоматизировать планирование дня через голос и текст в мессенджерах  
**Решение:** Веб-приложение с фоновыми ботами: принимает голосовые и текстовые сообщения в Telegram и MAX, распознаёт дату/время на русском языке, создаёт события в Google Calendar, присылает напоминания (за 1 час, 15 мин, 5 мин), утренний обзор дня. Дашборд в браузере с управлением ботами, просмотром событий и логами в реальном времени  
**Результат:** Двойное резервирование (Telegram + MAX) — если один бот упал, второй продолжает работу. Системный трей Windows, авто-перезапуск при падении, автозагрузка с Windows. Два независимых Google-календаря  
**Стек:** Python, Flask, Waitress, Bootstrap 5, python-telegram-bot, Google Calendar API, MAX API, speech_recognition, pydub + FFmpeg, APScheduler, pystray, PyInstaller  
**Статус:** ✨ Активный проект  
**Ссылки:** [📖 Документация](https://github.com/Murs2024/Luma2025-docs#readme) | [Презентация](https://drive.google.com/file/d/1VOQDzXNttiAvN56zSeW7cCY7up1MJkxa/view?usp=sharing)

---


### 🎯 Murs Media — GUI для загрузки и конвертации медиа (форк youtube-dl-gui)
**Задача:** Дать на Windows удобный интерфейс к yt-dlp и ffmpeg без ручного набора команд и путей в консоли  
**Решение:** Настольное приложение WinForms вызывает внешний yt-dlp для извлечения потоков, опционально ffmpeg для склейки форматов и конвертации; быстрая и подробная загрузка, пакетные режимы, настройки и релизный конвейер под бренд Murs Media  
**Результат:** Один exe (портативная сборка), русскоязычный интерфейс, обновления через отдельный updater, сценарии подготовки релиза на GitHub; поддержка пользовательских аргументов и расширенных форм загрузки  
**Стек:** C#, .NET Framework 4.7.2, Windows Forms, yt-dlp (внешняя зависимость), ffmpeg (внешняя зависимость), MSBuild  
**Статус:** ✨ Активный проект  
**Ссылки:** [📖 Документация](https://github.com/Murs2024/youtube-dl-gui-master-docs#readme) | Демо по запросу

---


### 🎯 Hair Salon Bot — Telegram-бот с RAG-поиском по базе знаний ухода за волосами
**Задача:** Автоматизировать персональный график ухода за тонкими пористыми волосами без фиксированного расписания «по дням недели»  
**Решение:** Telegram-бот с памятью состояния, RAG-поиском по структурированной базе знаний (ИИ-fallback при отсутствии точного совпадения), адаптивным циклом (гладкость → восстановление → гладкость → стекло), ежедневными напоминаниями и генерацией премиум PDF-протокола с актуальным графиком  
**Результат:** Stateful-ассистент с inline-кнопками и защитой от ошибок (дубли, перезапись «вчера»); салонное стекло по запросу; автопересборка PDF после изменений; timezone-aware напоминания  
**Стек:** Python, python-telegram-bot, APScheduler, ReportLab, python-dotenv, Pillow, RAG (ChromaDB, embeddings)  
**Статус:** ✨ Активный проект  
**Ссылки:** [📖 Документация](https://github.com/Murs2024/hair-salon-bot-rag-docs#readme) | [Демо в Telegram (@salonMurka_bot)](https://t.me/salonMurka_bot) — тестовый доступ с паролем (уточняйте в [Telegram](https://t.me/murs51Luma))

---

## 🛠️ Технологии

**LLM и AI:** YandexGPT, GigaChat, DeepSeek, ChatGPT  
**Разработка и автоматизация:** Python, SaleBot, RAG, LangChain  
**Интеграции и инфраструктура:** Google API, SQL, Git, WordPress, Telegram API

---

## 📊 GitHub-статистика

[![GitHub followers](https://img.shields.io/github/followers/Murs2024?style=flat-square)](https://github.com/Murs2024?tab=followers)  
[![GitHub stars](https://img.shields.io/github/stars/Murs2024?affiliations=OWNER%2CCOLLABORATOR&style=flat-square)](https://github.com/Murs2024?tab=repositories)  
[![Profile views](https://komarev.com/ghpvc/?username=Murs2024&style=flat-square)](https://github.com/Murs2024)

- 👤 Профиль: [github.com/Murs2024](https://github.com/Murs2024)
- 📚 Репозитории: [github.com/Murs2024?tab=repositories](https://github.com/Murs2024?tab=repositories)

---

## 🎯 Что я ищу

- Проекты в **Legal Tech** и **AI-автоматизации**
- Сотрудничество по разработке **ботов и ассистентов**
- Интеграция AI в **действующие бизнес-процессы**
- Одноразовые проекты и долгосрочные партнерства

---

## 📞 Контакты и портфолио

| Канал | Ссылка |
|-------|--------|
| 💬 **Telegram** (быстрый ответ) | [@murs51Luma](https://t.me/murs51Luma) |
| 📧 **Email** | uristpro51@gmail.com |
| 🔗 **GitHub** | [github.com/Murs2024](https://github.com/Murs2024) |
| 💜 **Boosty** (блог, поддержка **Murs Media**) | [boosty.to/murs_exl2026](https://boosty.to/murs_exl2026) |
| 💼 **FL.ru портфолио** | [fl.ru/users/oasheveleva51/portfolio](https://www.fl.ru/users/oasheveleva51/portfolio/) |
| 🎨 **Kwork** | [kwork.ru/user/shev51](https://kwork.ru/user/shev51) |
| 🏢 **Zerocoder** | [marketplace.zerocoder.ru/profile](https://marketplace.zerocoder.ru/profile) |
| 📰 **Telegram-канал** | [t.me/+i6iFdfPAQaQ3ZjUy](https://t.me/+i6iFdfPAQaQ3ZjUy) |
| 🌐 **Личный сайт** | [uristpro51.ru](https://uristpro51.ru/) |

---

## 🤝 Открыта к сотрудничеству

Готова к проектам в Legal Tech, AI-автоматизации и разработке ботов/ассистентов.

**💬 Лучший способ связи: Telegram [@murs51Luma](https://t.me/murs51Luma)**
