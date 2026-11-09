---
type: component
created: 2026-11-08
tags:
  - taskflow
  - component
depends_on:
  - "[[Task Repository]]"
  - "[[Task Model]]"
---

# Task Service

Task Service - компонент бізнес-логіки застосунку TaskFlow.

## Основні функції

- Створення нового завдання.
- Редагування наявного завдання.
- Видалення завдання.
- Зміна статусу та пріоритету.
- Перевірка коректності введених даних.

## Призначення

Компонент обробляє запити користувача та взаємодіє зі сховищем даних через Task Repository.

## Типізовані зв'язки

- depends_on: [[Task Repository]]
- depends_on: [[Task Model]]

## Інші зв'язки

- [[Task]]
- [[Task Status]]
- [[Task Priority]]
