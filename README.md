## Ecommerce Applications
## Milestone 1: Project Overview
Authentication : login logout signup
Product page: All the products
Orders page : Shows orders for each user
Payment gateway
## Milestone 2:
Setting up of the frontend with following commands and packages

tailwind CSS
React (npm create vite@latest frontend)
setting up of the backend with following commands and packages npm init || npm init -y

express (npm i express)
mongoose (npm i mongoose)
cors (npm i cors)
nodemon (npm i nodemon)
## Milestone 3
Setting up of nodejs sevrer and handling the api requests.
Connect your application to MongoDB to store and manage data.
connetion between Database and server.
Error Handler (these handler rectify where has the error occured filename.js)
## Milestone 4
User Model for our database, (Done)
setting up controllers to handle user-related data,
enabling file uploads using Multer.

## Milestone 5
Created a signup page
Created validation Object using RegEx
Setup React-Router for the Present Pages

## Milestone 7
Created two routes signup and login

For Signup:

Take the data sent by the user
const {name, email, password} = req.body
check if user is already present in the DB
if Yes-> return saying user is already present , Direct Login
If No->
Hash the password (Bcrypt.js, argon2.js)
Create a user and store the name, email, password in DB
For Login:

Take the data sent const {email, password} = req.body
check if the user entry is present in DB also compare the password.
If Yes-> create a token and send that as cookies
If No-> return saying Signup first

## Milestone 8
Card Componet
Display of all the products with dummy data in Home page.

## Milestone 9
Created Product Entry Form
Used form data to send the data over the network call.

## MileStone 10
Product Schema
cerate end point to wirte the data into DB.
Cloudinary, multer

## Milestone 11
Wirting the GET endpoint to fetch the data from DB and send to the client.


## Milestone 12
Adding products dynamically into the home page

## Milestone 13 (Updation)
Backend: PUT route for updateing
Frontend: Page for auto filling the updated data [id] except images fetch data from backend and once we have data in frontend we fill the input boxes with that data

## milestone 14
DELETE route in the backend
Delete button at the frontend

## MileStone 15
Added Navbar component (Mobile Responsive with Drop Down)

## MileStone 16
Added Single Page product Details
Created Image Modal Component

## MileStone 17
Cart Schema,
cart route
Cart Controller [get and addToCart]

## MileStone 18
Get Cart Data Route
