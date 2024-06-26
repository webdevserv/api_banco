# Bank API

> Bank API built with [Node.js](https://nodejs.org) + [Express](https://expressjs.com/).

The API is already built for you and not part of the exercise.

Refer to https://aka.ms/NodeBeginner (videos 17 through 21 covers this exact API).

> Note: all entries are stored in-memory and are not persisted, so when the server is stopped all data is lost.

## API details

Route                                        | Description
---------------------------------------------|------------------------------------
GET    /api/                                 | Get server info
POST   /api/accounts/                        | Create an account, ex: `{ user: 'Uxue', description: 'Travel', currency: 'EUR', balance: 500 }`
GET    /api/accounts/:user                   | Get all data for the specified account
DELETE /api/accounts/:user                   | Remove specified account
POST   /api/accounts/:user/transactions      | Add a transaction, ex: `{ date: '2024-07-24T18:40:43.500Z', object: 'Flight', amount: -2000 }`
DELETE  /api/accounts/:user/transactions/:id | Remove specified transaction

