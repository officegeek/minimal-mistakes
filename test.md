```mermaid
graph TD
    SM[Search Module] -->|access| DA[Database Access]
    BM[Booking Module] -->|access| DA
    DA -->|retrieves/stores data| DB[(Database)]
    BM -->|initiates| PG[Payment Gateway]
```
