---
type: component
created: 2026-11-08
tags:
  - taskflow
  - component
governed_by:
  - "[[SQLite Storage Decision]]"
depends_on:
  - "[[Task Model]]"
---

# Task Repository

Task Repository - компонент доступу до даних застосунку TaskFlow.

## Основні функції

- Збереження завдань у SQLite.
- Отримання завдань із бази даних.
- Оновлення записів.
- Видалення записів.
- Пошук завдань за заданими параметрами.

## Призначення

Компонент забезпечує зберігання даних між запусками програми та відокремлює SQL-запити від бізнес-логіки.

## Типізовані зв'язки

- governed_by: [[SQLite Storage Decision]]
- depends_on: [[Task Model]]

## Інші зв'язки

- [[Task Service]]
- [[Task]]
