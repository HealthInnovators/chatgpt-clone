## ChatGPT Clone

## Pre-requisites

- Install VS Code - https://code.visualstudio.com/download
- Install node js - https://nodejs.org/en/download
- Get Google Gemini API key - https://aistudio.google.com/
- Create Blob store on Vercel at http://www.vercel.com/
- Create Postgres database on Vercel at http://www.vercel.com/

#### Install all the packages:

`npm install --legacy-peer-deps`

#### In the .env.local file, add the Google Gemini API key, Blob token, and Postgres url

#### Sync the database

`npm run db:generate`

`npm run db:migrate`

#### Run Locally

`npm run dev`
