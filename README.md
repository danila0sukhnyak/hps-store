### Магазин

```mermaid
    erDiagram
    PRODUCT ||--|{ SIZES :  contains
    PRODUCT ||--|| BRAND :  contains
    PRODUCT ||--|| TYPE :  contains
    PRODUCT ||--|{ SEX :  contains
    PRODUCT ||--|{ SEASON :  contains
    PRODUCT ||--|{ COLOR :  contains
    ORDER ||--|| DELIVERY : contains
    ORDER ||--|| USER : contains
    ORDER_PRODUCTS ||--|{ PRODUCT : contains
    ORDER_PRODUCTS ||--|{ ORDER : contains
    USER ||--o{ DELIVERY : save
```
