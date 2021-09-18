# restaurant-finder
Building a Yelp clone using the PERN stack, with the guidance of 
[Sanjeev Thiyagarajan](https://www.youtube.com/watch?v=7qAXvOFhlDc&t=11s).


## Getting Started

1. Create the `.env` file in the server folder.
2. Update the .env file with your correct local information 
  PORT="choose a port number"

  PGUSER="Your PG username"
  PGHOST=localhost
  PGPASSWORD="Your password"
  PGDATABASE="the name of you db"
  PGPORT="Insert your PG port number"

3. Install dependencies in the server folder and in the client folder: `npm i` or `yarn install`

4. Run the server: `nodemon server.js`
  - Note: nodemon is used, so you should not have to restart your server
5. Run the client: `yarn start` and visit http://localhost:3000/ if it's not automatically done for you.