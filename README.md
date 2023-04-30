# graphql-demo
Simple project using GraphQL


## Test the app
1. Start the app
2. Go to http://localhost:8080/graphiql
2. Type in the query and hit the play button at the top of the windo
```
query bookDetails {
  bookById(id: "book-1") {
    id
    name
    pageCount
    author {
      id
      firstName
      lastName
    }
  }
}
```