# Метрики ARPU и ARPU cumulative

## Определения
1. **ARPU (Average Revenue Per User)** — средний доход на одного активного пользователя за определённый период времени:
$$
ARPU = \frac{\text{Общий доход}}{\text{Количество активных пользователей}}
$$

2. **ARPDAU (Average Revenue Per Daily Active User)** — средний доход на одного активного пользователя за один день:
$$
ARPDAU = \frac{\text{Общий доход за день}}{\text{Количество активных пользователей за день}}
$$

3. **ARPMAU (Average Revenue Per Monthly Active User)** — средний доход на одного активного пользователя за месяц:
$$
ARPMAU = \frac{\text{Общий доход за месяц}}{\text{Количество активных пользователей за месяц}}
$$

4. **Cumulative ARPU** — кумулятивный средний доход на пользователя, учитывающий доход за весь период с начала использования:
$$
\text{Cumulative ARPU} = \frac{\text{Кумулятивный доход}}{\text{Общее количество пользователей}}
$$

## Применение
- **ARPU** позволяет оценить, насколько эффективно монетизируются активные пользователи.
- **ARPDAU** полезен для анализа краткосрочной эффективности ежедневных действий, таких как акции или обновления.
- **ARPMAU** помогает оценить долгосрочные тренды монетизации.
- **Cumulative ARPU** используется для сравнения качества привлечённого трафика и выбора оптимального CPI.

## Примеры
1. Для оценки разных проектов сравниваются их ARPU: проект с более высоким ARPU считается более успешным в плане монетизации.
2. **Cumulative ARPU** используется для выбора оптимального CPI: если стоимость установки превышает кумулятивный ARPU, кампания становится убыточной.

## Ограничения
- Эти метрики не учитывают распределение доходов между пользователями (например, долю платящих пользователей).
- Кумулятивный ARPU может быть менее полезен для игр с длинным жизненным циклом, где ранние доходы значительно превышают текущие.