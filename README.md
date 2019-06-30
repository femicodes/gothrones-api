# gothrones-api

An API wrapper for the [Game of Thrones API](https://anapioficeandfire.com/)

### Technologies
1. Node.js
2. Express.js


#### BaseURL: localhost/api/

### Endpoints:
#### BOOKS

- **`GET` /books**
  -  Get all books.
- **`GET` /books/name**
  - Get book by name.
- **`GET` /books/?fromReleaseDate=x**
  - Books that were released after, or on, the given date are included in the response.
- **`GET` /books/?toReleaseDate=x**
  - Books that were released before, or on, the given date are included in the response.
- **`POST` /books/:userID/comment**
  - Users can comment on a book.
- **`GET` /randomBooks**
  -  Get a random book


#### CHARCTERS

- **`GET` /characters**
  -  Get all characters.
- **`GET` /characters/?name=x**
  -  Characters with the given name are included in the response.
- **`GET` /characters/?gender=x**
  -  Characters with the given gender are included in the response.
- **`GET` /characters/?culture=x**
  -  Characters with the given culture are included in the response.
- **`POST` /characters/:userID/comment**
  - Users can comment on a character.
- **`GET` /characters/random**
  -  Get a random character
- **`GET` /characters/playedBy**
  -  Get the name of the actor of this character


#### HOUSES

- **`GET` /houses**
  -  Get all houses
- **`GET` /houses/?name=**
  -  Get the name of this house.
- **`GET` /houses/?region=x**
  -  Get the region that this house resides in.
- **`GET` /houses/currentLord**
  -  Get the character of this house's current lord.
- **`GET` /houses/heir**
  -  Get the character of this house's heir.
- **`GET` /houses/randomHouse**
  -  Get a random house


### TV SERIES

- **`GET` /?tvSeries**
  -  Get the seasons a character acted in.


### USERS

- **`GET` /auth/signup**
  -  Creates a new user

- **`GET` /auth/login**
  -  User login
