## Fullstack open - Graphql

### Exercises of fullstack open part 8

Through the exercises, we will implement a GraphQL backend for a small library

8.1 The number of books and authors  
Implement queries `bookCount` and `authorCount` which return the number of books and the number of authors.

8.2 All books

Implement query allBooks, which returns the details of all books.

In the end, the user should be able to do the following query:

```
query {
  allBooks {
    title
    author
    published
    genres
  }
}

```
