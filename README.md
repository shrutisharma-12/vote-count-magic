# 🗳️ Voting System

A secure voting platform for small-to-medium elections with authentication, vote receipts, and audit logs. Built with **React**, **Spring Boot**, and **PostgreSQL**.

---

## Features
- Create/manage elections (single-choice or ranked-choice)  
- Voter registration and authentication  
- Cast votes with receipt verification  
- Append-only audit log  
- Real-time and end-of-election tallying  
- Export results (CSV / PDF)  

---

## Quick Start

### Database
```sql
CREATE DATABASE voting_db;
cd backend
# configure application.properties
mvn clean install
mvn spring-boot:run
cd frontend
npm install
npm start
Contributing

Fork → branch → add features/tests → PR

Follow Java/React coding standards
