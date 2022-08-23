
# Rate-It-Backend 


Backend files for Rate-It Frontend

The Frontend Files can be found at [Rate-It-Project](https://github.com/ayushi-8102/Rate-It)


<h4 align="left">Languages and Tools:</h4>
<p align="left"> <a href="https://expressjs.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/expressjs/expressjs-ar21.svg" alt="express" height="40"/> </a> <a href="https://git-scm.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://heroku.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/heroku/heroku-icon.svg" alt="heroku" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank"> <img src="https://img.icons8.com/color/48/000000/html-5.png"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"> <img src="https://img.icons8.com/color/48/000000/javascript.png"/> </a> <a href="https://www.mongodb.com/" target="_blank"> <img src="https://www.vectorlogo.zone/logos/mongodb/mongodb-icon.svg" alt="mongodb" width="50" height="50"/> </a> <a href="https://nodejs.org" target="_blank"> <img src="https://img.icons8.com/color/48/000000/nodejs.png"/> </a> <a href="https://postman.com" target="_blank"> <img src="https://www.vectorlogo.zone/logos/getpostman/getpostman-icon.svg" alt="postman" width="40" height="40"/> </a></p>


### The following API calls can be made with this project

***

#### GET Requests

* > __/browse/leaderboard__

It scans the database and an array containing the movieID and the votes casted to that movie in decreasing order is returned.

<br>

* > __/browse/list?email=\<email\>__

The array of movies nominated by the user with the passed email is returned.

<br>

* > __/browse/find?email=\<email\>&id=\<movieID\>__

Returns a boolean value true if the movie is nominated by the passed user or false if the movie isn't nominated by the user.

<br>

* > __/browse/remove?idu=\<email\>&idm=\<movieID\>__

Deletes the tuple which has the passed email and movieID.

<br>

* > __/browse/add?userID=\<email\>movieID=\<movieID\>__

Pushes the values of movieID and userID into the database.

***

### Setting Up the Project

1. Clone the repo
   ```sh
   git clone 
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Create a .env file using the template .env.template and add values accordingly.
   
### Usage

1.  To run the server
    ```sh 
    npm start 
    ```
***

