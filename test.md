```mermaid
graph TD
    SM[Search Module] -->|uses| DB[(Database)]
    BM[Booking Module] -->|uses| DB
    BM -->|initiates payment via| PG[Payment Gateway]
    SM -->|search request to| HD[Hotel Data API]
```
