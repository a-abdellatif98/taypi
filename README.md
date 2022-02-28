# README

An Implementation for <a href="https://www.apollographql.com/blog/community/backend/using-graphql-with-ruby-on-rails/">Using graphql with ruby on rails</a>


# Query 

  ```{
  items {
    id
    title
    description
      artist {
       firstName
       lastName
       email
       createdAt
    }
   }
}
```
