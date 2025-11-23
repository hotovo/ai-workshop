# 01 – Database & TypeORM Setup (SQLite)

## Goal

Have a working SQLite database, TypeORM data source, and seeded `User` entity.

## Tasks

- Complete the TypeORM data source (`src/db/data-source.ts`).
- Create `User` entity with fields:
  - `id`, `firstName`, `lastName`, `email`, `company`, `role`
  - `status` (`prospect | active | churned`)
  - `notes` (nullable)
  - `createdAt`, `updatedAt`
- With AI assistance:
  - Generate 10–20 mock users.
  - Create `scripts/seed.ts` that wipes + inserts users.
- Run the seed script and confirm database is populated.

## Tips (use your AI!)

- Ask AI to scaffold the entity class.
- Ask AI to create clean mock users with realistic combinations.
- Ask AI to generate the seed script with proper imports and a safe reset.

Continue to **02**.
