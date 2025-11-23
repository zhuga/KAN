---
name: Requirement Change / Изменение требования
about: Request a change to project requirements / Запрос на изменение требований проекта
title: '[REQ-CHANGE] '
labels: requirement, documentation
assignees: ''
---

## Идентификатор требования / Requirement ID

RQ-XXX (из REQUIREMENTS_TRACKING.md)

## Текущее требование / Current Requirement

Процитируйте текущую формулировку требования.
Quote the current requirement statement.

## Предлагаемое изменение / Proposed Change

Новая формулировка требования.
New requirement statement.

## Обоснование / Justification

Почему это изменение необходимо?
Why is this change necessary?

- Бизнес-причины / Business reasons:
- Технические причины / Technical reasons:
- Влияние на проект / Project impact:

## Анализ влияния / Impact Analysis

### Затронутые компоненты / Affected Components

Перечислите компоненты, которые потребуют изменений:
- [ ] `automated_rag_pipeline.py`
- [ ] `intelligent_rag_system.py`
- [ ] `legal_document_versioning.py`
- [ ] `museum_mcp/` (MCP сервер)
- [ ] `knowledge_graph.json`
- [ ] Другое / Other: _______________

### Затронутые требования / Affected Requirements

Перечислите связанные требования из:
- REQUIREMENTS_TRACKING.md: RQ-XXX, RQ-YYY
- REQUIREMENTS_INTEGRATION_MATRIX.md: зависимости
- PROJECT_REQUIREMENTS_MANAGEMENT_SYSTEM.md: процессы

### Затронутая архитектура / Affected Architecture

Какие архитектурные документы требуют обновления?
- [ ] UPDATED_ARCHITECTURE.md
- [ ] SYSTEM_DEPENDENCY_MAP.md
- [ ] architecture.md

## Оценка рисков / Risk Assessment

| Риск / Risk | Вероятность / Probability | Влияние / Impact | Митигация / Mitigation |
|------------|---------------------------|------------------|----------------------|
| Нарушение обратной совместимости | Высокая/Средняя/Низкая | Критическое/Высокое/Среднее | План действий |
| Потеря данных | Высокая/Средняя/Низкая | Критическое/Высокое/Среднее | План действий |
| Снижение производительности | Высокая/Средняя/Низкая | Критическое/Высокое/Среднее | План действий |

## План реализации / Implementation Plan

### Этап 1: Документирование
- [ ] Обновить REQUIREMENTS_TRACKING.md
- [ ] Обновить REQUIREMENTS_VERSION_CONTROL.md
- [ ] Обновить REQUIREMENTS_INTEGRATION_MATRIX.md
- [ ] Обновить архитектурные документы

### Этап 2: Разработка
- [ ] Обновить код компонентов
- [ ] Обновить тесты
- [ ] Проверить на реальных данных (5,104+ документов)

### Этап 3: Валидация
- [ ] Подтвердить соответствие STRICT правилам
- [ ] Проверить сохранение полной функциональности
- [ ] Валидировать работу с реальными данными

## Соответствие STRICT правилам / STRICT Rules Compliance

- [ ] Изменение НЕ упрощает функционал
- [ ] Изменение НЕ создаёт упрощённых версий
- [ ] Изменение сохраняет работу с реальными данными
- [ ] Изменение согласовано с архитектурой
- [ ] Изменение документировано полностью

## Одобрение / Approval

**КРИТИЧНО**: Изменения требований должны быть одобрены:
- [ ] Ответственным за требования / Requirements Owner
- [ ] Архитектором проекта / Project Architect
- [ ] Мейнтейнером проекта / Project Maintainer

## Дополнительный контекст / Additional Context

Любая дополнительная информация о предлагаемом изменении.
Any additional context about the proposed change.
