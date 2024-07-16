# Welcome to Flights Service

## Project Setup
- clone the project on you local
- Execute `npm install` on the same path as of you root directory of the downloaded project
- create a `.env` fiel in the root directory and add the following environment variable
    - `PORT=3000`
- Inside the `src/config` folder create a new file `config.json` and then add the following piece of json

```
{
     "development": {
    "username": <YOUR _DB_LOGIN_NAME>,
    "password": <YOUR _DB_PASSWORD>,
    "database": "Flights_Search_DB_Local_DEC",
    "host": "127.0.0.1",
    "dialect": "mysql"
  }
}

```
- once you've added your db config as listed above,go to the src folder from your terminal and execule the `npx squelize db:create`
