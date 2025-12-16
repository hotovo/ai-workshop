# 05 – AI Features Inside the CRM

## Goal

Add AI-powered actions to the user detail page.

## Feature Options (choose at least one)

### 1. AI Summary

- Button “Generate AI Summary”.
- Calls `/api/ai/user-summary/[id]`.
- Renders a short summary panel.
- (Optional) Save into `notes`.

### 2. AI Email Draft

- Button “Generate Email”.
- Calls `/api/ai/user-email/[id]`.
- Shows:
  - Subject
  - Body (textarea)
- (Optional) Add tone: friendly | formal | playful.

### 3. AI Tags / Segmentation

- Add `tags` to `User` entity.
- Create `/api/ai/user-tags/[id]`.
- LLM returns tag suggestions.
- Render tags as Tailwind badges.

## Tips

- Rely heavily on your coding assistant to iterate prompts.
- Ask AI to ensure output is well-structured JSON.

Proceed to **06**.
