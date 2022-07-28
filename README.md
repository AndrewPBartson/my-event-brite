# MyEventBrite

### Deep Stack Program - 11/21 to 1/22
- Instructor - Kalpana Viswanathan / Kal Academy
- Team members
  - Swati Tayal
  - Priya Kamble
  - Farkhondeh
  - Andrew Bartson
---

### Tech Stack
- Microservices (9) in Docker containers
- ASP.Net Core MVC
- ASP.Net Core Authentication
- Microsoft Entity Framework Core 3.1 
- Microsoft MSSQL Server
- Redis cache
- RabbitMQ message broker

### Actions available to Users
  - Browse events
  - Filter events by location, category, price, and date
  - Add tickets for an event to cart
  - Pay for tickets
---
## APIs

### Event API - Open Data
  - Event presentation API
  - Event location API
  - Event category API
  - Event format API
  - Picture API
  - Ticket availability API

### TokenService API - Authentication
  - for register and login
  - Logged-in users receive a token
  - Token allows the user to access the secure APIs

### Cart API - Shopping Cart
- Users add tickets to cart
- Contents of cart are saved in Redis cache

### Order API - Checkout
- Users pay for tickets using Stripe

---

## Docker Containers
1) UI / Web MVC - Frontend
5) Event API - Access information about events
2) MSSQL database server - for Event API
3) Token Service API - Authentication
2) MSSQL database server - for Token Service API
6) Cart API - Shopping cart
7) Redis cache - for Cart API
7) Order API - Payment services
4) RabbitMQ - Messaging between microservices

---
  
### Documentation
- Swagger is configured to provide complete API documentation
---

### Videos
- [1 - First efforts](https://youtu.be/6cUGzwwzMZ0) 

- [2 - Making progress](https://youtu.be/YwbV9ZY5AGs) 

- [3 - Final demo - featuring all team members](https://youtu.be/nzRd_yhs6-s)

---

