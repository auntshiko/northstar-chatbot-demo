# Northstar Website AI Assistant Demo

Reusable portfolio demo for a knowledge-grounded website chatbot.

## What it demonstrates
- Responsive customer-facing chat UI
- Retrieval from an approved business knowledge base
- Visible answer sources
- Safe fallback when the knowledge base cannot answer
- Suggested questions
- API boundary ready to replace the deterministic demo responder with an LLM provider

## Run
`npm install`
`npm run dev`

## Production adaptation
Replace the KB array with client content or retrieval from CMS/docs/database. In `app/api/chat/route.js`, pass retrieved context to the client's chosen LLM provider and instruct it to answer only from that context. Keep API credentials server-side.
