## MERN + GraphQL sample CRUD app (A todo app)
MERN Stack Tutorial for Beginners by Ben Awad/Edureka.

#### Steps to run:
* Install MongoDB, and start it.
* Run the server app with `node index.js` (in server folder). Use http://localhost:4000/ for the GraphQl playground
* Run the client react app with `node index.js` (in client folder) Use http://localhost:3000/ for the React app (built using CRA)

#### Relevant Links:
* https://mongoosejs.com/docs/  
* https://github.com/prisma/graphql-yoga

* https://material-ui.com/getting-started/installation/  
* https://material-ui.com/demos/paper/#paper

* https://www.apollographql.com/docs/angular/features/cache-updates.html

#### Steps done:
(Server)  
* Install `graphql-yoga`. Copy the starter code from the github link and run index.js  
* Add mongoose. Wire it up, define the schema for Todo model  
* Create a mutation type for doing create/update/remove  
* Test everything in playground

(Client)  
* Create a CRA app. (`npm install -g create-react-app`)  
* Add apollo libs and setup ApolloProvider, ApolloClient  
* Use gql and add Todos query to fetch our list items. Use compose.  
* Add material UI and add a `<List>` to display & render items
* Setup update & remove. Use the update feature in apollo to force a refresh of the screen (by default it caches for optmization)  
* Add a `<Text>` and set up a create operation.
