# Ant Academy - Pharaoh Backend

"As part of my internship at Ant Colony, I had the opportunity to work with my collegues on the backend development using Node.js and MongoDB as the primary database. My responsibilities included designing and implementing RESTful APIs to handle data retrieval and manipulation, as well as integrating various third-party services to enhance functionality.

This is how site looks like 

https://www.figma.com/file/iYWrMNjpePQwGAX4j6X4fc/AC---Internal-Tool?type=design&node-id=38-660&mode=design&t=l9BIxCZbwvS3RF9K-0

## Manual Installation

Clone the repo,

Install the dependencies:

```bash
npm install
```

Set the environment variables:

```bash
cp .env.example .env
# open .env and modify the environment variables
```

## Table of Contents

- [Commands](#commands)
- [Environment Variables](#environment-variables)

## Commands

Running in development:

```bash
# seed the database with default users:
# tarik.velic@ses.edu.ba    Majmun12
npm run seed 

npm run dev
```

## Environment Variables

The environment variables can be found and modified in the `.env` file.

```bash
# Port on which backend will run 
PORT = <value>
# URL of frontend application
FRONTEND_URL = "<value>"
# URL of the Mongo DB
DB_CONNECTION_STRING = "<value>"
# Secret string used for signing JWT tokens
JWT_SECRET = "<value>"
```

