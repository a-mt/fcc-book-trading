# Manage a Book Trading Club

## Install

* Install dependencies

    ```
    npm install
    ```

* Create .env

    ```
    GOOGLE_BOOK_KEY=""
    MONGO_URI="mongodb://"
    ```

* Run

    ```
    npm run start
    ```

## User Stories

* As an unauthenticated user
  * I can view all books posted by every user

* As an authenticated user
  * I can update my settings to store my full name, city, and state
  * I can add a new book  
        Uses Google Books API
  * I can propose a trade and wait for the other user to accept the trade

Exemple :  
http://bookjump.herokuapp.com/

https://www.googleapis.com/books/v1/volumes?q=abundance