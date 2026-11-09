---
type: component
created: 2026-11-08
tags:
  - taskflow
  - component
represents:
  - "[[Task]]"
---

# Task Model

Task Model - компонент, який визначає структуру даних завдання.

## Основні поля

- id - унікальний ідентифікатор.
- title - назва завдання.
- description - опис.
- priority - пріоритет.
- status - статус виконання.
- due_date - кінцевий термін виконання.

## Призначення

Компонент використовується для представлення завдань у програмному коді та передачі даних між іншими модулями.

## Типізовані зв'язки

- represents: [[Task]]

## Інші зв'язки

- [[Task Status]]
- [[Task Priority]]
- [[Task Service]]
- [[Task Repository]]
