E-Commerce Web API


# Introduction
This repository is related to YouTube Tutorial of The Complete E-Commerce Web API Using Node.js With Express & MongoDB.

[Watch here](https://youtu.be/sH5L-yOI3_8)


# Run

### Install

```
npm install
```

### Start API

```
npm start
```

# Routes

### Products

```
GET      /api/v1/products
GET      /api/v1/products/:id
POST     /api/v1/products
PUT      /api/v1/products/:id
DELETE   /api/v1/products/:id
GET featured products: /api/v1/products/get/featured/:count
GET products count: /api/v1/products/get/count
```

### Categories
```
GET      /api/v1/catgories
GET      /api/v1/categories/:id
POST     /api/v1/categories
PUT      /api/v1/categories/:id
DELETE   /api/v1/categories/:id
```

### Users

```
GET      /api/v1/users
GET      /api/v1/users/:id
POST     /api/v1/users
PUT      /api/v1/users/:id
DELETE   /api/v1/users/:id
GET users count: /api/v1/users/get/count
```

#### Register new user

```
POST     /api/v1/users/register
```

#### Login user

To login the user and get the auth token you can use:

```
POST     /api/v1/users/login
```
