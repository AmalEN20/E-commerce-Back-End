<!-- omit in toc -->
# E-Commerce Back End

<!-- omit in toc -->
## Description
Build the back end for an e-commerce site using the provided Express.js API and configuring it to use Sequelize so that it interacts with MySQL database.

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
<video src="https://user-images.githubusercontent.com/116880367/230572736-0711dff0-7408-4728-9c09-23f1cf247cb1.mp4"></video>
