### P2P platform

```mermaid
    erDiagram
    CHAT ||--|{ USERS :  contains
    USERS }|--|| CHAT :  contains
    USERS ||--o{ ADS :  contains
    ADS ||--|{ CATEGORY : contains
    COMPLAINTS ||--|{ USERS : contains
    COMPLAINTS ||--|{ ADS : contains
    COMPLAINTS ||--|{ COMPLAINTS_TYPE : contains
    
```
