## SPOTIFY EXPRESS

<p align="center">
  <img src="./img/spotify-express.png" width="500">
</p>

This is my first back-end project, made with Express.js. You can search in Spotify for artists and see their albums and play 30 seconds of preview the tracks availables.

You can run the final project deployed here: https://spotify-express.herokuapp.com/

### **Features**

- You can search in Spotify by artist.
- Lots of artists that matched with your entered keyword will appear.
- When select an specific artist, will appear all his albums.
- And when a click is made in an album, all the tracks will be load and if it's available, will be possible to play a 30 seconds preview of every track.
- Since any page it's possible to come back to homepage to made a new search.
- The data has been obtained from Spotify official API.


### **What I learned**

- Basic Express.js operation.
- Create routes with GET method.
- Render different HTML with different routes.
- Keep secure my API keys with Dotenv.
- When and how to use req.query and req.params.
- How to read official API documentation.
- Deploy a back-end project with Heroku.


### **Resources**

- Initial concert picture from [Freepik](https://www.freepik.es).
- Spotify icon from [Font Awesome](https://fontawesome.com/icons?d=gallery).
- This project was created with [Express.js](http://expressjs.com/), a Node.js web application framework.
- Spotify API from [Spotify for Developers](https://developer.spotify.com/dashboard/login).
- Deploy application with [Heroku](https://dashboard.heroku.com).


### **Usage**

To run in local server, you need Node.js and Express.js.

- Install Node.js at the terminal if you haven't yet (https://nodejs.org/es/).

- You will need to install the package manager npm:

```bash
sudo apt-get install npm
```
- Clone or download the repository in your computer.

```bash
git clone https://github.com/diana-moreno/spotify-express.git`
```
- Download the npm competitions in your own repository and start it.

```bash
npm install
```
- Install Express.js:

https://expressjs.com/en/starter/installing.html

- Install all the dependencies of production and development that are detailed in the json file:

```bash
  "dependencies": {
    "dotenv": "^8.1.0",
    "ejs": "^2.7.1",
    "express": "^4.17.1",
    "express-handlebars": "^3.1.0",
    "hbs": "^4.0.4",
    "spotify-web-api-node": "^4.0.0"
  },
  "devDependencies": {
    "nodemon": "^1.19.2"
  },
```

- To start the server you can type the following command (it is the valid command in production).

```bash
npm start
```
- If you preffer, you can run this command, but only in development, will not work in production (this avoids you to restart the server in every change).

```bash
npm run start-dev
```
- I utilized Heokuapp to deploy my project. You can run the final project deployed here:

https://spotify-express.herokuapp.com/

