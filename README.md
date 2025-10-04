# 📨 Taj Messenger

Современное и стильное приложение для обмена сообщениями, построенное на Flutter и Supabase.
Проект создан с нуля с использованием Material 3, светлой/тёмной темы и мощных инструментов Supabase для аутентификации, уведомлений и статуса присутствия.

## 📸 Скриншоты

*Вставьте сюда ваши скриншоты. На GitHub это можно сделать простым перетаскиванием картинок в текстовое поле.*

| Список чатов | Экран чата | Профиль |
| :---: | :---: | :---: |
| ![Chat List]("C:\Users\developer\Downloads\Telegram Desktop\photo_2025-10-04_14-27-54.jpg") | ![Chat Screen]("C:\Users\developer\Downloads\Telegram Desktop\photo_2025-10-04_14-27-56.jpg") | ![Profile Screen](ПУТЬ_К_СКРИНШОТУ_3.png) |


## ✨ Функционал

* ✅ Регистрация и вход через Supabase Authentication
* ✅ Онлайн-статус пользователей в реальном времени
* ✅ Push-уведомления через NotificationService
* ✅ Поддержка Material 3 (M3)
* ✅ Две темы интерфейса: светлая и тёмная
* ✅ Адаптивный и современный дизайн
* ✅ Логика авторизации и чатов разделена по слоям (чистая архитектура)

## 🛠️ Стек технологий

* Flutter (Material 3, Dart)
* Supabase (Auth, Database, Realtime)
* Firebase Messaging / Local Notifications (для уведомлений, если будет интеграция)
* Provider / Riverpod (по необходимости)
* MVC / Clean архитектура

## 🧠 Что изучаешь с этим проектом

* Работа с Supabase Auth & Database
* Подключение push-уведомлений
* Управление онлайн-статусом пользователей
* Построение архитектуры на сервисах
* Настройка Material 3 UI с кастомными темами

## 🧑‍💻 Автор
* Фарзод Сомони
* 📍 Таджикистан, г. Душанбе 
* 💬 Flutter Developer | Building modern mobile apps
* 🌐 [Твой GitHub профиль](https://github.com/somoni69)

## 🗂️ Структура проекта

```plaintext
lib/
 ├── main.dart                # Точка входа
 ├── supabase_config.dart     # Конфигурация Supabase
 ├── screens/
 │   ├── auth_screen.dart     # Экран авторизации
 │   └── chat_list_screen.dart # Список чатов
 ├── services/
 │   ├── auth_service.dart    # Авторизация
 │   ├── presence_service.dart# Онлайн-статус
 │   └── notification_service.dart # Уведомления


