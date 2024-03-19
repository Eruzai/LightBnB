# LightBnB Project

A simple multipage web-app used to get familiar with postgreSQL, writing queries, and database creation and integration to a server.

## Getting Started

1. [Create](https://github.com/Eruzai/LightBnB/tree/main) a new repository using this repository as a template.
2. Clone your repository onto your local device.
3. Install dependencies using the `npm install` command.
4. Start the web server using the `npm run local` command. The app will be served at <http://localhost:3000>.
5. Install and run [PostgreSQL](https://www.postgresql.org/) for your machine.
6. Create tables
  ```
  psql
  \c lightbnb
  \i ./migrations/01_schema.sql
  ```
7. Fill tables with seed data
  ```
  \i ./seeds/01_seeds.sql
  \i ./seeds/02_seeds.sql
  ```
8. Go to <http://localhost:3000> in your browser.

## Dependencies

- bcrypt 3.0.6
- cookie-session 1.3.3
- express 4.17.1
- nodemon 1.19.1
- pg 8.11.3

## Features

- user registration
- new listing creation
- property search by name, price, and rating
- user's listings and reservations pages