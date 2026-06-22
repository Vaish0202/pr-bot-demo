# PR Bot — AI Code Review + Weekly Digest

Automated GitHub PR reviewer and weekly digest built with n8n + OpenRouter.

## What it does
- **Workflow 1:** Reviews every PR automatically and posts an AI summary as a GitHub comment
- **Workflow 2:** Every Sunday, emails a weekly code health digest with stats and AI narrative

## Tech stack
- n8n (workflow automation)
- GitHub API (PR data + comments)
- OpenRouter (LLM — free tier)
- Gmail (digest delivery)

## Setup
1. Import both workflow JSONs from `/workflows` into your n8n instance
2. Add credentials: GitHub token, OpenRouter API key, Gmail OAuth
3. Update repo owner and name in the HTTP Request nodes
4. Activate both workflows

## Demo
<img width="1228" height="727" alt="image" src="https://github.com/user-attachments/assets/f612a29b-61d8-4dfd-b477-75d7824144fd" />

