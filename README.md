# retail-back-end
An Express.js API, configured to use Sequelize to interact with a MySQL database. I wrote the sequelize models and relationships for Category, Product, ProductTag, and Tag; and wrote RESTful routes to GET, PUSH, PUT, and DELETE to/from Category, Product, and Tag.

## Installation
- Open terminal at application folder.
- Install dependencies `npm i`.
- Create .env file and paste the following lines, changing the DB_USER and DB_PW to your MySQL credentials if necessary.
```
DB_NAME=ecommerce_db
DB_USER=root
DB_PW=password
```
- Start the MySQL shell and log in `mysql -u root -p`.
- Source the database `source db/schema.sql`.
- Quit the MySQL shell `quit`.
- Seed the database `npm run seed`.

## Usage
- Start the application `npm start`.
- See video below for example usage in Insomnia:

https://user-images.githubusercontent.com/82857538/129472542-9b5119a9-3758-4e2d-ae5d-a9bb03aa0b28.mov
