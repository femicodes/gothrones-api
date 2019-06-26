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
- **`GET` /books/fromReleaseDate**
  - Books that were released after, or on, the given date are included in the response.
- **`GET` /books/toReleaseDate**
  - Books that were released before, or on, the given date are included in the response.
- **`POST` /books/:name/comment**
  - Users can comment on a book.
- **`GET` /randomBooks**
  -  Get a random book


#### CHARCTERS

- **`GET` /characters**
  -  Get all characters.
- **`GET` /characters/name**
  -  Characters with the given name are included in the response.
- **`GET` /characters/gender**
  -  Characters with the given gender are included in the response.
- **`GET` /characters/culture**
  -  Characters with the given culture are included in the response.
- **`POST` /characters/:name/comment**
  - Users can comment on a character.
- **`GET` /characters/randomCharacter**
  -  Get a random character
- **`GET` /characters/playedBy**
  -  Get the name of the actor of this character


#### HOUSES

- **`GET` /houses**
  -  Get all houses
- **`GET` /houses/name**
  -  Get the name of this house.
- **`GET` /houses/region**
  -  Get the region that this house resides in.
- **`GET` /houses/currentLord**
  -  Get the character of this house's current lord.
- **`GET` /houses/heir**
  -  Get the character of this house's heir.
- **`GET` /houses/randomHouse**
  -  Get a random house


### TV SERIES

- **`GET` /tvSeries**
  -  Get the seasons a character acted in.


### USERS

- **`GET` /auth/signup**
  -  Creates a new user

- **`GET` /auth/login**
  -  User login