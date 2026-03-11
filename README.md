# SafePath - Backend API

## Application Database

**Application DB Connection String:** `postgresql://db_appdb_69b1bb0ca4b255a975a16530_user:ba7D4ravMnAOsxxxWwccfgn%2AJR5cm%2A0V@ep-delicate-pine-aj8o1nmt.c-3.us-east-2.aws.neon.tech:5432/AppDB_69b1bb0ca4b255a975a16530?sslmode=require`

## Web API

**WebApi URL:** https://webapi69b1bb0ca4b255a975a16530-production.up.railway.app

**Swagger API Tester URL:** https://webapi69b1bb0ca4b255a975a16530-production.up.railway.app/swagger

## Google APIs (Gemini, Maps, Speech-to-Text)

The backend can use a Google API key provided via the **GOOGLE_API_KEY** environment variable (set on Railway). Use it for Gemini LLM, Maps, and Speech-to-Text. Check **GET /api/google/status** and **GET /api/google/health** to verify the key is set and reachable.

## Recommended Tools

**Recommended SQL Editor tool (Free):** [pgAdmin](https://www.pgadmin.org/download/)

## Deployment

This backend is configured for Railway deployment using nixpacks.toml.
