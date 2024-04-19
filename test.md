```mermaid
graph LR
    UI[User Interface] -->|interacts with| WI[Web Interface]
    WI -->|sends data to| BA[Backend Application]
    BA -->|processes data| DB[(Database)]
    DB --> BA
```
