
# E-commerce Back End

## Description

This project is the back end for an e-commerce site. It uses the latest technologies, including Express.js, Sequelize, and PostgreSQL, to build a robust and scalable backend. The application allows for full CRUD (Create, Read, Update, Delete) operations on categories, products, and tags. This backend is not deployed but can be tested locally using Insomnia Core or Postman.

## Table of Contents

- [E-commerce Back End](#e-commerce-back-end)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Walkthrough Video](#walkthrough-video)
  - [Screenshot](#screenshot)
  - [License](#license)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ecommerce-backend.git
   ```
2. Navigate into the project directory:
   ```bash
   cd ecommerce-backend
   ```
3. Install the necessary dependencies:
   ```bash
   npm install
   ```
4. Set up your environment variables:
   - Rename `.env.EXAMPLE` to `.env` and update it with your PostgreSQL credentials.

5. Create the database schema:
   ```bash
   psql -U postgres -f db/schema.sql
   ```
6. Seed the database with initial data:
   ```bash
   npm run seed
   ```

## Usage

To start the server, run:
```bash
npm start
```

The server will start and sync Sequelize models to the PostgreSQL database.

You can now use Insomnia Core or Postman to test the API routes.

## Walkthrough Video

A walkthrough video demonstrating the functionality of the application is available [here](https://drive.google.com/file/d/1MspS01DzHm4YXf_whhnsetftflyjijbp/view).

- The video shows:
  - How to set up the database schema using the PostgreSQL shell.
  - How to seed the database.
  - How to start the server.
  - Testing of all GET, POST, PUT, and DELETE routes using Insomnia Core.

## Screenshot

Include a screenshot of your API routes being tested in Insomnia Core.

![Screenshot](images/Screenshot%202024-08-18%20032554.png)

## License

This project is licensed under the MIT License.
