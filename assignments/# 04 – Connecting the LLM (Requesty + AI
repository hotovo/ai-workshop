# 04 – Connecting the LLM (Requesty + AI SDK)

## Goal

Wire up the AI client using the `ai` SDK and a real Requesty key.

## Tasks

- Add to `.env.local`:
  REQUESTY_API_KEY=...
- Create `src/lib/aiClient.ts`:
- Configure the AI SDK for Requesty.
- Export:

  - `generateUserSummary(user)`
  - `generateUserEmail(user, options?)`

- Create API routes:
- `/api/ai/user-summary/[id]`
- `/api/ai/user-email/[id]`
- Each should:
- Load user from DB.
- Call the AI client.
- Return structured JSON.

## Tips

- Ask AI to scaffold the client wrapper.
- Let AI propose prompt structure and parameters.
- Ensure the response format is predictable.

Move to **05**.
