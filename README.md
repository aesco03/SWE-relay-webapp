# SWE-relay-webapp

### 1. Ignore/do not edit 
- node_modules
- .gitignore
- tsconfig.json

### 2. Create a .env.local in /relay-app root dir to store your API and DB keys
___
## Web App architecture layout & description

```text
SWE-project-root/
├── relay-app/   
│ |── src/app/           ← Next.js App Router (pages routes & API routes)
│     |   ├── page.tsx
│     |   ├── layout.tsx
│     |   ├── globals.css
│     ├── dashboard/
│     │   └── page.tsx
│     └── api/
│       └── transcription/
│ 
├── public/               ← All image files and artifacts stored here (e.g. .png, .jpg, .svg)
├── components/           ← Reusable UI components (root level)
│   ├── Header.tsx
│   ├── RequestCard.tsx
│   └── TranscriptionTool.tsx
├── lib/                  ← Utility functions & configurations (root level)
│   ├── auth.ts
│   ├── assemblyai.ts
│   └── payments.ts
├── next.config.ts        ← config file (keep this)
├── package.json
└── tsconfig.json
```
