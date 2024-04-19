```mermaid
flowchart LR
    User -->|requests booking| Booking_System[Booking System]
    Booking_System -->|retrieves availability| Hotel_Database[Hotel Database]
    Hotel_Database --> Booking_System
    Booking_System -->|returns options| User
    User -->|selects room & dates| Booking_System
    Booking_System -->|processes booking| Payment_Gateway[Payment Gateway]
    Payment_Gateway -->|confirms transaction| Booking_System
    Booking_System -->|confirms booking| User
```
