# RALPH

Personal AI assistant. Built by Rafael.

## Setup

1. Add `ANTHROPIC_API_KEY` in Vercel → Settings → Environment Variables
2. Deploy
3. Open on iPhone Safari → Share → Add to Home Screen

## Files

- `index.html` — frontend
- `api/chat.js` — serverless function that forwards requests to Anthropic
- `vercel.json` — routing config
- `package.json` — Node runtime declaration

## Stack

- Vercel (hosting + serverless)
- Anthropic Claude Sonnet 4.5
- iOS Safari voice input + speech synthesis
