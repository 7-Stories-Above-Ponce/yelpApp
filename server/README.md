This is a Yelp app that allows others to find restaurants in different cities, as well as their ratings.

- $ npm install -g npx
- $ npx create-react-app

- $ mkdir pg-api && cd pg-api
- $ npm init -y
- $ touch server.js
- $ npm install --save body-parser morgan pg express cors

---

# PostgreSQL

Create database using psql powershell and connect with the database

**create database**

- $ psql
  postgres=# create database;
  CREATE DATABASE

**Connect with database**
postgres=# \c ;

![](psqlImage/connect.png)

**Connect with restaurant table**

![](psqlImage/restaurants.png)

**Connect with review table**!

![](psqlImage/review.png)

**Select from restaurants table**!

![](psqlImage/select.png)

**Select from review table**!

![](psqlImage/connectr.png)
