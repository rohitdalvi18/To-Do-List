# To-Do-List

A To-Do-List Node application with MongoDB.

## Usage

- Clone the repo.
- To install the dependencies:

```
npm i
```

- Get [MongoDB](https://www.mongodb.com/cloud/atlas) Authentication Credentials by creating a Cluster and then create a database. For more refer [MongoDB Atlas Docs](https://docs.atlas.mongodb.com/)
- Create a `.env` file and enter the following:

```
MONGO_URL="your_url_goes_here"
```

_Make sure you have put the database name at the end of the URL_

- To run the application in the root directory run:

```
node app.js
```

- To create a new list you need make a `*get*` request: `/:customListName`
