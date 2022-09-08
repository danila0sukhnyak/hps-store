### P2P platform

```mermaid
    erDiagram
    USERS ||--o{ ADS :  contains
    USERS ||--o{ DELIVERY :  contains
    ADS ||--|{ CATEGORY : contains
    COMPLAINTS ||--|{ USERS : contains
    COMPLAINTS ||--|{ ADS : contains
    ORDER ||--|{ DELIVERY : contains
    ORDER ||--|{ ADS : contains
    ORDER ||--|{ USERS : contains
    CHAT ||--|{ USERS :  contains
    USERS }|--|| CHAT :  contains
```


