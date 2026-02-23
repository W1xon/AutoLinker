<div align="center">

# 🔗 AutoLinker
<h3><i>Автоматическое подключение к онлайн-занятиям</i></h3>

[![Version](https://img.shields.io/badge/version-1.1.1-cyan.svg?style=for-the-badge)](https://github.com/W1xon/AutoLinker/releases)
[![Platform](https://img.shields.io/badge/platform-Windows-0078d7.svg?style=for-the-badge)](https://dotnet.microsoft.com/download)
[![License](https://img.shields.io/badge/license-MIT-green.svg?style=for-the-badge)](LICENSE)

<img src="Assets/Logo.png" width="50%" alt="AutoLinker">

**AutoLinker** — десктопное приложение для автоматического поиска и открытия ссылок на занятия в личном кабинете вуза.

Программа анализирует расписание, определяет актуальную пару и подключается к ней без ручного поиска по порталу.

[Скачать последнюю версию](https://github.com/W1xon/AutoLinker/releases/latest) • [Сообщить о проблеме](https://github.com/W1xon/AutoLinker/issues)

</div>

---

## Что делает AutoLinker

Каждый день одно и то же: открыть портал, авторизоваться, найти дисциплину, проверить время, открыть ссылку.

AutoLinker автоматизирует этот процесс:

- Определяет ближайшее занятие по расписанию
- Проверяет соответствие времени
- Находит актуальную ссылку на странице дисциплины
- Подключается автоматически или по нажатию кнопки
- Работает в фоновом режиме через трей
- Есть возможность отправки уведомлений в Telegram

Приложение не требует постоянного участия пользователя после первоначальной настройки.

---

## Технологии

- **WPF (.NET)** — десктопный интерфейс с тёмной темой
- **Playwright** — автоматизация браузера
- Логика сопоставления расписания и содержимого страницы
- Автоматическая проверка обновлений через GitHub

---

## Установка

1. Перейдите в раздел Releases.
2. Скачайте `AutoLinker.exe`.
4. Запустите.
5. Один раз укажите данные для входа в личный кабинет.

> При первом запуске может загрузиться браузерный движок Playwright (~100–200 MB). Это нормальный процесс и требуется только один раз.

---

## Скриншоты

<div align="center">
  <img src="Assets/main.png" width="49%" alt="Main Window">
  <img src="Assets/settings.png" width="49%" alt="Settings Window">
</div>

---

<div align="center">
  <p><b>Автор:</b> Wixon</p>
</div>
