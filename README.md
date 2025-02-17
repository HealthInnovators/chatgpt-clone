## ChatGPT Clone

## Pre-requisites

- Install VS Code - https://code.visualstudio.com/download
- Install node js - https://nodejs.org/en/download
- Get Google Gemini API key - https://aistudio.google.com/
- Create Blob store on Vercel at http://www.vercel.com/
- Create Postgres database on Vercel at http://www.vercel.com/

#### Install all the packages:

pnpm install

#### Add variable to the .env.local file, 

- Add the Google Gemini API key
- Add random secret
- Blob token, and
- Postgres url

#### Sync the database

pnpm run db:generate

pnpm run db:migrate

#### Run Locally

pnpm run dev
