# AMAZON CLONE 
# ECommerce Website

- HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
- JavaScript: ES6+, Array Functions, Rendering System
- Node & Express: Web API, Body Parser, File Upload, JWT
- MongoDB: Mongoose, Aggregation
- Development: ESLint, Babel, Git, Github,

### 1. Setup MongoDB
 - Download and Install it from [mongodb.com](https://www.mongodb.com/try/download/community)

### 2. Create .env file
- Create .env file in project folder
- Enter these lines to that:

```
MONGODB_URL=mongodb://localhost/jsamazona
JWT_SECRET=somethingsecret
PAYPAL_CLIENT_ID="your paypal client id" or sb
```

### 3. Run Backend

```
$ npm install
$ npm run build
$ npm start
```

### 4. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 5. Create Admin User

- Run this on chrome: http://localhost:5000/api/users/createadmin
- Note admin email and password

### 6. Admin Login

- Run http://localhost:8080/#/signin
- Enter admin email and password and click signin
- Click Dashboard Link on Header Menu
- Click Products on left sidebar
- Click Create Product Button
- Enter Product Information
- Go to home page (http://localhost:8080) and test Ecommerce Website


# Features

1. Home Screen
   1. Static Web Page Design
   2. CSS Grid to create website layout
   3. Flexbox to shape product thumbnails and responsive design
2. Product Screen
   1. create single page application
   2. Create buttons and add events to buttons
3. Cart Screen
   1. Save and retrieve data in local storage
   2. Master in javascript array functions
   3. Use combo box and add event to it
   4. re-render screen based on changes in item count
4. Sign-in and Register Screen
   1. Create dynamic form
   2. Input validation in frontend and backend
   3. Create web server using node.js
   4. Connect to Mongodb database
   5. Add registered user to the database
   6. Authenticate user based on email and password
   7. Using Jsonwebtoken to authorize users
5. Shipping and Payment Screen
   1. Create wizard form to get user data in multiple steps
   2. Save user info in the local storage
6. Place Order Screen
   1. Validate and create order in the database
7. Order Screen
   1. Payment with paypal
   2. Show order state based on user and admin activities
8. Profile Screen
   1. Create authenticated routes
   2. enable user to update their informations
   3. enable user to logout and clear local storage
   4. show list of orders to user and link it to details
9. Dashboard Screen
   1. Create professional dashboard using pure CSS
   2. Using chart library to show sales information
10. Order Screen
    1. Enable admin to mange orders
    2. show loading message and alert message
11. Product Screen
    1. enable admin to manage products
    2. upload product images to server
