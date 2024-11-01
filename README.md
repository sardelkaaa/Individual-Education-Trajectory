# Individual-Education-Trajectory
University Project
```mermaid
graph LR
    subgraph Внешняя среда
        A[Абитуриенты]
        B[Студенты]
        C[Куратор]
        D[РОПы]
    end

    subgraph Система
        Z{Рекомендательный сервис ИОТ}
    end

    A --> Z
    B --> Z
    C --> Z
    D --> Z

    subgraph База данных
        E{Курсы}
        F{Компетенции}
        G{Профессии}
    end

    Z --> E
    Z --> F
    Z --> G

    subgraph Внешние системы
        H[Система управления контентом]
        I[Система аутентификации]
        J[Система аналитики]
    end

    Z --> H
    Z --> I
    Z --> J
```
