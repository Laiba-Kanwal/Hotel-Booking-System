## Hotel Management System (MERN Stack)
 Project Objective:
This project is a web-based Hotel Management System built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows hotel administrators to manage bookings, users, and room availability efficiently.

## Usage
Simply click on the demo link provided.
If you wish to download the code and use it, you must first download zip file.
If you want to use your own MongoDb Atlas server, you must configure the .env file with your MongoDB database and then run ```npm install ``` to install the dependencies and then start the server with ```npm start ```

If you just want to use the client then simply go to the client folder, run ```npm install ``` to install the dependencies and then start the client with ```npm start ```

## Features
* Fullstack MERN Hotel Website that utilizes CRUD functionality 
* Users can browse rooms and create bookings on selected dates
* Users enter their details in a checkout form to create a booking and store their information
* Backend handles date collision's and notifies user's if a room is available or unavailable on the selected dates
* User can view and delete their bookings by entering the provivded confirmation code or email
* Room and booking data is stored within a MongoDB databse
* Website is fully responsive and looks great across multiple platforms


## Technologies
The app was created with the following technologies
* MongoDB
* Express.JS
* ReactJS
* Redux
* NodeJS
* SASS


## What I Learned
Using what I learned on my last MERN stack project, I decided to further advance my knowledge on the backend as well as implementing the state management tool called Redux into my website. I quickly found the value of using Redux as a state managemen tool as I no longer had to pass down a ton of props into child components, but rather simply calling it from the Redux store. I do admit that setting up the boiler plate was a bit of a challenge as well as understanding why I needed to use Redux middlewares such as thunk. I am glad though that I decided to utilize Redux from the start as I could see that trying to implement it into an existing project being a challenge.
I also learned alot more about the backend and using MongoDB as a databse. I decided to store all malleable data in the database as well as data such as booking details that can be created or deleted. One of the biggest challenges was handling date collisions. If a user searches for a room that has already been booked on a specified date, the user won't be able to boom that room. As a result I learned a lot about MongoDB objects and how to manipulate data on the backend in order to show that a room is unavaiable.
In the end I gained a great deal of knowledge and I'm looking forward to start creating larger and more ambituous projects.






