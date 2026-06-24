# 🏢 Apartment Service Platform (Microservices – Spring Boot 3 + Angular

## 📌 Overview
This project is a **hyperlocal service marketplace** for apartment residents.

Users can:
- Request services (taxi, repair, babysit, errands)
- Accept jobs (provider side)
- Chat in realtime
- Manage requests lifecycle

---

## 🎯 Vision

Build a **real-world microservice system**:
- Realtime service matching
- AI-assisted interaction

## STRUCTURE
### backend/
  * gateway-service/
  * auth-service/
  * request-service/
  * chat-service/

### frontend/
  * angular-app/

### infra/ (future)

## Strategy Pattern
### RequestHandler
  * ├── TaxiHandler
  * ├── RepairHandler
  * ├── BabysitHandler
  * └── MarketplaceHandler
