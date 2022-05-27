# employee-tracker

## User Story
AS A manager at an internet retail company

I WANT a back end for my e-commerce website that uses the latest technologies

SO THAT my company can compete with other e-commerce companies

## Usage
From the command line the user will go into MySQL shell by entering `mysql -uroot -p` and providing their password when prompted. The user will then create the database by running `source file-path/file-name`. In this case, `source db/schema.sql`. Then exit MySQL shell with `\q`.

The database can be seeded by running `npm run seed`.

The server can then be started with `npm start`.

In Insomnia the user can GET all the routes for the full databases by using the URL http://localhost:3001/api/ + either "tags", "products" or categories. The user can also add "/:id" to the end of the URL to view a specific ID. They then have the option to add (POST), update (PUT) or delete (DELETE) an ID.

## Walkthrough Video
https://drive.google.com/file/d/12BKY78hpshv28wRp4deUgzAwFhGjVrWe/view?usp=sharing 

## Preview of application
![preview of application](./assets/images/preview.png)

## Packages Used
mySQL2 Package

Sequelize

dotenv package

## GitHub Repository
https://github.com/randronaco1027/ecommerce_backend