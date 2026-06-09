# Dot Variant Generator / Генератор вариантов email с точками

**[Live Deployment / Живая версия](https://neverlolser.github.io/xdot-xgenerator/)**

---

## 🇺🇸 English

Dot Variant Generator is a serverless, simple yet powerful web application designed to generate unique email dot variants (such as `john.doe@gmail.com`, `j.o.h.n.d.o.e@gmail.com`).

### Why do you need dots in your email?
Many services (like Gmail) ignore dots (`.`) in the username part of an email address. This means that `johndoe@gmail.com`, `john.doe@gmail.com`, and `j.o.h.n.d.o.e@gmail.com` all deliver mail to the exact same inbox!

**Why is this useful?**
* **Account Organization:** You can sign up for the same website multiple times using different dot variants of your email, but still receive all notifications in one single inbox.
* **Tracking & Filters:** You can use specific dot variants for specific subscriptions to easily filter them or see who sold your email data.

### How it works
This tool takes your base email username (the part before the `@`) and your selected domain (e.g., `@gmail.com`), and automatically generates a mathematical variation of dots between the letters that you haven't used before. It keeps track of the variants you've generated so you never get a duplicate!

### Features
- **Fully Serverless:** No backend needed! Works directly in your browser.
- **Local Storage Persistence:** All of your active domains, generation history, and settings are saved securely in your browser's local storage.
- **Unique Pattern Generation:** Automatically creates unique patterns without duplicates.
- **History Tracking:** A built-in history modal allows you to view, access, and copy all previously generated variants.
- **Domain Management:** Easily add and manage different email domains.
- **Bilingual:** Fully supports English and Russian interfaces.

### How to Use Locally
Simply download or clone this project and double-click `index.html` to open it in your web browser. Everything runs locally out of the box!

---

## 🇷🇺 Русский

Генератор вариантов с точками (Dot Variant Generator) — это простое, мощное веб-приложение без серверной части, созданное для генерации уникальных вариантов email с точками (например, `john.doe@gmail.com`, `j.o.h.n.d.o.e@gmail.com`).

### Зачем нужны точки в email?
Многие почтовые службы (например, Gmail) игнорируют точки (`.`) в имени пользователя. Это означает, что письма, отправленные на `johndoe@gmail.com`, `john.doe@gmail.com` и `j.o.h.n.d.o.e@gmail.com`, придут в один и тот же почтовый ящик!

**Чем это полезно?**
* **Мультиаккаунты:** Вы можете регистрироваться на одном и том же сайте несколько раз, используя разные варианты email с точками, но при этом получать все уведомления в один ящик.
* **Фильтрация и отслеживание:** Используйте определенные варианты для конкретных подписок, чтобы легко фильтровать почту или узнать, кто слил ваши данные.

### Как это работает
Инструмент берет базовое имя вашего ящика (часть до `@`) и выбранный домен (например, `@gmail.com`), а затем автоматически генерирует математическую комбинацию точек между буквами, которую вы еще не использовали. Приложение запоминает сгенерированные варианты, чтобы исключить повторения!

### Особенности
- **Полностью без сервера:** Бекэнд не нужен! Работает прямо в вашем браузере.
- **Хранение данных:** Все ваши активные домены, история генераций и настройки надежно сохраняются в LocalStorage вашего браузера.
- **Уникальная генерация:** Автоматически создает уникальные паттерны без дубликатов.
- **История:** Встроенное окно истории позволяет просматривать и копировать все ранее созданные варианты.
- **Управление доменами:** Легко добавляйте и управляйте различными почтовыми доменами.
- **Двуязычность:** Полная поддержка английского и русского интерфейсов.

### Как использовать локально
Просто скачайте или клонируйте этот проект и дважды кликните по файлу `index.html`, чтобы открыть его в веб-браузере. Все работает локально прямо "из коробки"!
