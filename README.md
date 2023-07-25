# Ant Academy - Pharaoh Backend

This project builds RESTful APIs using Node.js, Express and Mongoose

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

