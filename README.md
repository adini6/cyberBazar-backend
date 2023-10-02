# cyberBazar Backend
cyberBazar Backend is an e-commerce back end built with Express.js and Sequelize ORM.

## Table of Contents

- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [License](#license)
- [Credit](#credit)
- [Questions](#questions)

## Technologies Used

- Node.js
- Express.js
- MySQL2
- Sequelize ORM
- Dotenv

## Installation

1. **Clone the Repository**

   ```sh
   git clone https://github.com/adini6/cyberBazar-backend.git
   cd cyberBazar-backend
   ```
2. **Install Dependencies**

    ```sh
    npm install
    ```

3. **Set up Environment Variables**
    - Create a .env file in the root directory.
    - Add your MySQL user and password in the .env file.  

    ```sh
    DB_NAME='ecommerce_db'
    DB_USER='your_mysql_username'
    DB_PW='your_mysql_password'
    ```
4. **Run the Schema**
    - Open MySQL shell and run the following command:
    ```sh
    source db/schema.sql
    ```
    - Exit the MySQL shell by running exit.
5. **Seed the Database**
    ```sh
    npm run seed
    ```
6. **Start the Server**
    ```sh
    npm start
    ```

## Usage

Once the server is up and running, you can use Insomnia Core or any other API testing tools to test the API routes:

- The `/api/categories` endpoint
- The `/api/products` endpoint
- The `/api/tags` endpoint

## Features 

- API routes for products, categories, and tags.
- Database interactions through Sequelize ORM.
- Error handling.

## License 

This project is licensed under the MIT License.

## Credit

- Starter coded clone from: https://github.com/coding-boot-camp/fantastic-umbrella

## Questions 

If you have any questions or insights feel free to reach out to me via email or through my github profile:

- [Github](https://github.com/adini6)
- [Email](mailto:adini18@gmail.com)