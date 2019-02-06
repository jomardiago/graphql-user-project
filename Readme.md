# graphql-user-project
A small GraphQL project that is using GraphQL as a query language. This project will expand to using ReactJS, once ReactJS is fully integrated, you can still use GraphiQL tooling to experiment on the project.

This project is intended as sort of a note, whether syntactically so that author can check how to for example create a 
new GraphQL Query or Mutation.

## Running the Project
If you want to run this project, just clone or download the project.

**Step 1:** Install all dependencies by typing `npm install`, make sure that you are on the location where you cloned or downloaded the
project.

The project is running a fake full rest API using [json-server](https://github.com/typicode/json-server). With that, you need to 
run 2 scripts using npm to successfully run the project.

**Step 2:** First we're going to run the main project by typing `npm run dev`. This will run our server.js using nodemon.
**Step 3:** Now we're going to run the fake rest API by typing `npm run json:server` on another tab of your terminal or 
another terminal.

The project will run **localhost:4000** while the server will run on **localhost:3000**

Finally, go to your browser of choice and type **localhost:4000/graphql**. This will open the GraphiQL tool and you're on! Get to 
experimenting by adding new resources in our db.json file and adding new Queries and Mutations to your schema.js file.

Happy Coding :+1:
