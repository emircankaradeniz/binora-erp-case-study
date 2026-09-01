# Architecture Notes

## Main Modules

- Identity and user management
- Property and unit management
- Financial operations
- Debt and payment workflows
- Cashbox management
- Reporting
- Background jobs
- Data migration

## Infrastructure

```text
Frontend
   ↓
Backend API
   ↓
Business Services
   ↓
PostgreSQL

Additional Services:
- Worker
- Redis
- Docker
```

## Design Priorities

- Data consistency
- Financial accuracy
- Historical data preservation
- Multi-tenant separation
- Operational continuity
