# nodejs-docker-template

Simple template for NodeJS development with Docker

---

### Docker Commands

> The `docker` and `docker-compose` commands were implemented in `package.json` and can be called through npm

- Running API and MySQL with docker compose: `npm run compose:up`
- Running API and MySQL with docker compose with detached mode: `compose:up -d`
- Running docker compose down: `compose:down`

---

### Database Commands

> Were created with `sequelize-cli` commands and scripts for easy database manipulation

- Creating database: `npm run db:create`
- Dropping database: `npm run db:drop`
- Creating tables: `npm run db:sync`

---
