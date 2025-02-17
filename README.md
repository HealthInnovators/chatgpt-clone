## ChatGPT Clone

## Pre-requisites

- Install VS Code - https://code.visualstudio.com/download
- Install node js - https://nodejs.org/en/download
- Get Google Gemini API key - https://aistudio.google.com/
- Create Blob store on Vercel at http://www.vercel.com/
- Create Postgres database on Vercel at http://www.vercel.com/

#### Install all the packages:

npm install --legacy-peer-deps

#### Add variable to the .env.local file, 

- Add the Google Gemini API key
- Add random secret
- Blob token, and
- Postgres url

#### Sync the database

npm run db:generate

npm run db:migrate

#### Run Locally

npm run dev
