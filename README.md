<!-- omit in toc -->
# E-Commerce Back End

<!-- omit in toc -->
## Description

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Installation
- Install Node.js v16
- Install MySQL Server
- Install Insomnia
- Install npm packages:
  ```
  npm install
  ```
## Usage
1. Change the name of `.env.EXAMPLE` file to `.env`
2. Enter your MySQL username and MySQL password in the `.env` file:
3. Create and select your database with MySQL shell commands:
    ```
    mysql -u root -p
    ```
    ```shell
    mysql> source db/schema.sql;
    mysql> quit;
    ```
4. Seed the test data to your database:
    ```
    npm run seed
    ```
5. Execute the app and run the server:
    ```
    npm start
    ```
6. Use Insomnia to test API POST, GET, PUT, DELETE routes.

- Walkthrough video
<video src=""></video>
