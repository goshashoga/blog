---
title: Git
summary: Система управления версиями Git
date: 2024-09-07

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'

authors:
  - admin
  - Ted

tags:
  - Academic
  - Hugo Blox
  - Markdown
---

Управление версиями с помощью Git
Git — это распределённая система управления версиями (VCS), которая используется для отслеживания изменений в коде и совместной работы над проектами. С её помощью можно сохранять все изменения в проекте, возвращаться к предыдущим версиям и параллельно разрабатывать разные функции (ветки).

Основные концепции Git:
Репозиторий: Хранилище проекта, в котором сохраняется вся история изменений.
Коммит (commit): Снимок текущего состояния файлов проекта. Каждый коммит хранит изменения и позволяет вернуться к конкретному моменту разработки.
Ветки (branches): Механизм для параллельной работы над разными версиями проекта. Основная ветка по умолчанию — main или master. Дополнительные ветки используются для разработки новых функций, исправления ошибок и экспериментов.
Слияние (merge): Объединение изменений из одной ветки в другую.
Клонирование (clone): Создание копии удалённого репозитория на локальном компьютере.
Push и Pull: Команды для отправки изменений в удалённый репозиторий (push) и получения изменений из него (pull).

Основные команды Git:
git init — инициализация нового репозитория.
git clone — клонирование удалённого репозитория.
git add <файл> — добавление файлов в область подготовки (staging).
git commit -m "сообщение" — создание коммита с описанием изменений.
git status — отображение состояния репозитория.
git log — просмотр истории изменений.
git branch — управление ветками.
git merge <ветка> — слияние ветки с текущей.
git push — отправка изменений в удалённый репозиторий.
git pull — получение изменений из удалённого репозитория.
