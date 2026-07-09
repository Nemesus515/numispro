# NumisPro Architecture

Status: Draft

## Overview

NumisPro is built using a modern client-server architecture.

Frontend communicates with Backend through a REST API.

Backend works with PostgreSQL using Prisma ORM.

The project consists of five main modules:

- Authentication
- Catalog
- Collections
- Community
- Analytics

---

## Frontend

Technology:

- Next.js
- React
- TypeScript
- Tailwind CSS

Responsibilities:

- User Interface
- Search
- Collection management
- Coin pages

---

## Backend

Technology:

- NestJS
- TypeScript

Responsibilities:

- Business logic
- Authentication
- REST API
- Price calculations
- Notifications

---

## Database

Technology:

- PostgreSQL
- Prisma ORM

Main entities:

- User
- Coin
- Collection
- CollectionItem
- Series
- Variety
- Achievement
- Comment
- MarketPrice

---

## Storage

- Coin images
- User avatars
- Collection photos

---

## Future

- Mobile applications
- AI services
- Marketplace
- Public API
