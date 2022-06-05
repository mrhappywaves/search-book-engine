# <img src="https://img.icons8.com/ios-filled/50/undefined/books.png"/> search-book-engine

## <img src="https://img.icons8.com/ios-glyphs/30/undefined/overview-pages-4.png"/> Table of Contents

<details>
<summary><strong>Click to see the contents table</strong></summary>
  
- [Description](#description)
- [Project Details](#project-details)
- [Installation](#installation)
- [Usage](#usage)
- [Tools](#tools)
</details>

## Description | <img src="https://img.icons8.com/ios-glyphs/30/undefined/book.png"/>

Want to search for a book online based on any keyword? Well, I just so happened to have finished this project! I used MERN dev practices combined with google API to bring you ability to search books on Google, but without the "pesky" ads. How cool, right? But that's not all! You can also save books to a list, and when you have read the book, you can remove it from the list to keep that reading flow going.

## Project Details | <img src="https://img.icons8.com/ios-glyphs/30/undefined/about.png"/> 

- You got yourself a fully functioning Google Book API search engine built with a RESTful API.
- The app runs on GraphQL built with Apollo Server. 
- Overall the app is built using the MERN stack with a React front end. 
- MongoDB database is used for storing all your "valuables"
- Of course being a MERN stack you can see some Node.js/Express.js server and API code.
- Deployed on Heroku with MongoDB database using MongoDB Atlas. 

## Installation | <img src="https://img.icons8.com/ios-filled/50/undefined/software-installer.png"/> 

- [Github](https://github.com/mrhappywaves/search-book-engine)
- Clone the repository
- Install all the packages by running `npm i` in your IDE (Integrated Development Environment) 
- Start the app locally by running `npm run develop` 
- Alternatively run - `"concurrently \"cd server && npm run watch\" \"cd client && npm start\""`

## Usage | <img src="https://img.icons8.com/ios-filled/50/undefined/settings-3.png"/> 
- [Heroku Link](https://book-g-seaker.herokuapp.com/) - CLICK THE LINK TO TRY THE APP OUT
- `Sign Up` if you would like to try all the app "perks"
- Type book name in search field, or type any keyword you like. Click `Search` to view the books
- A button `Save this Book` on the bottom of the book will allow you to save a book on your virtual Bookshelf.
- To review and delete click the `See Your Books` on the `Navigation bar`.


https://user-images.githubusercontent.com/94947579/172042681-f1c89c87-de77-4304-a990-a9734f45bf67.mp4


## Tools | <img src="https://img.icons8.com/ios-filled/30/undefined/job.png"/> 
- Primary `client` side packages
  - [react-bootsrap](https://www.npmjs.com/package/react-bootstrap)
  - [jwt-decode](https://www.npmjs.com/package/jwt-decode)
  - [react](https://www.npmjs.com/package/react)
  - [react-dom](https://www.npmjs.com/package/react-dom)
  - [react-router-dom](https://www.npmjs.com/package/react-router-dom)
  - [react-scripts](https://www.npmjs.com/package/react-scripts)
  - [@apollo/client](https://www.apollographql.com/docs/react/)
  - [@apollo/react-hooks](https://www.npmjs.com/package/@apollo/react-hooks)

- `server` side packages
  - [apollo-server-express](https://www.npmjs.com/package/apollo-server-express)
  - [bcrypt](https://www.npmjs.com/package/bcrypt)
  - [express](https://www.npmjs.com/package/express)
  - [graphql](https://www.npmjs.com/package/graphql)
  - [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
  - [mongoose](https://www.npmjs.com/package/mongoose)
  - [nodemon](nodemon)
