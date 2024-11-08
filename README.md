# Make your Knowledge Base

## Overview

This is a project for Hack This Fall 2024. The goal is to create a single knowledge base where you can store all your important bookmarks and notes.

## RUN

```bash
deno -ER server.ts
# -ER for reading .env and reading files from disk
```

Get your free MongoDB URI from [MongoDB Atlas](https://www.mongodb.com/atlas/database)

```
# add mongodb uri to .env
MONGODB_URI=mongodb://localhost:27017/<<your database name>>
```

## Features

- Store all your bookmarks and notes in one place
- Search through your notes and bookmarks
- Categorize your bookmarks and notes using Gemini AI
- Add tags to your bookmarks and notes
- Add comments to your bookmarks and notes

## Technologies

- HONO/Astrojs
- Shadcn UI
- MongoDB
- Deno
