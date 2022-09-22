### P2P platform

```mermaid
    erDiagram
    PRODUCT }|--|| CATEGORY:  contains
    PRODUCT }|--|| PHOTOS:  contains
    PRODUCT ||--|| USERS: contains

    COMMENTS ||--|| PRODUCT: contains
    COMMENTS ||--|| USERS: contains
    COMMENTS ||--O| PHOTOS: contains
    
    CHAT ||--|| USERS: contains
    CHAT ||--|| USERS: contains
    CHAT ||--O| PRODUCT: contains
    
    ORDER }|--|{ PRODUCT: contains
    ORDER }|--|| USERS: contains
    ORDER ||--O| PAYMENT: contains
```


