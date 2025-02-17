## ChatGPT Clone

## Pre-requisites

Download code from here - https://github.com/HealthInnovators/chatgpt-clone/tree/main
Install VS Code - https://code.visualstudio.com/download
Install node js - https://nodejs.org/en/download
Get Google Gemini API key - https://aistudio.google.com/
Generate a random secret: https://generate-secret.vercel.app/32
Create Blob store on Vercel at http://www.vercel.com/
Create Postgres database on Vercel at http://www.vercel.com/

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
