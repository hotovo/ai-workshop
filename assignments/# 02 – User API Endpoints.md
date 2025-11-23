# 02 – User API Endpoints

## Goal

Expose REST-style user endpoints using Next.js App Router + TypeORM.

## Tasks

Create route handlers:

### GET /api/users

- Returns list of users.
- Supports optional:
  - `search`
  - `status`
  - `page`, `limit`

### GET /api/users/[id]

- Returns single user.
- Handles "not found" cleanly.

### (Optional) POST /api/users

- Create a new user using validated JSON body.

## Tips

- Ask AI to:
  - Generate Zod schemas for validation.
  - Scaffold boilerplate for App Router route handlers.
  - Propose pagination logic.
  - Handle error cases cleanly.

Move to **03**.
