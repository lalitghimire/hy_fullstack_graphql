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

8.3 All Authors  
Implement query `allAuthors`, which returns the details of all authors. The response should include a field `bookCount` containing the number of books the author has written.

8.4: Books of an author  
Modify the `allBooks` query so that a user can give an optional parameter author. The response should include only books written by that author.

8.5: Books by genre  
Modify the query `allBooks` so that a user can give an optional parameter genre. The response should include only books of that genre.

8.6: Adding a book  
Implement mutation `addBook`, which can be used like this:

```
mutation {
  addBook(
    title: "NoSQL Distilled",
    author: "Martin Fowler",
    published: 2012,
    genres: ["database", "nosql"]
  ) {
    title,
    author
  }
}
```
