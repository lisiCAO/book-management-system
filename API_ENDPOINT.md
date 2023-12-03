

### User API

1. **Register User**
   - `POST /users/register`
   - Description: register new users.

2. **User Login**
   - `POST /users/login`
   - Description: User Login.

3. **Get**
   - `GET /users/{userId}`
   - Description: get User by ID 

4. **Update**
   - `PUT /users/{userId}`
   - Description: update user's information

5. **Delete**
   - `DELETE /users/{userId}`
   - Description: delete user

### Book API

1. **Add**
   - `POST /books`
   - Description: Add new books.

2. **Get**
   - `GET /books`
   - Description: get all books

3. **Get One Book**
   - `GET /books/{bookId}`
   - Description: get book by  ID.

4. **Update**
   - `PUT /books/{bookId}`
   - Description: Update books

5. **Delete**
   - `DELETE /books/{bookId}`
   - Description: delete books

### Borrow API

1. **Borrow Books**
   - `POST /borrow/{userId}/{bookId}`
   - Description: user borrow books

2. **Return**
   - `POST /return/{userId}/{bookId}`
   - Description: User return books

3. **Search History**
   - `GET /records/{userId}`
   - Description: searching for borrowing history


