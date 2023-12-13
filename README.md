# GraphQL and Spring Boot
This application was created to show an example of using Spring and GraphQL
GraphQL API's were created to run queries, instead of usual REST API's

## Running
Just run the ```GraphQlSpringApplication```

## Testing
In order to test route to ```http://localhost:8080/graphiql?path=/graphql```
Two queries were created: allBooks and findOne
Test input: 
  
  query {
  allBooks {
    id
    pages
    author {
      firstName
      lastName
      }
    }
  }


  query {
  findOne(id: 2) {
    title
    pages
    }
  }
