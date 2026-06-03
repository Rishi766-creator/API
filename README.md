# Book Management API

A simple REST API built with Express.js to manage books.

## Setup

1. Initialize project:
```bash
npm init -y
```

2. Install dependencies:
```bash
npm install express
```

3. Run the server:
```bash
node server.js
```

Server runs at:
```
http://localhost:3000
```

## Book Object

```json
{
  "id": 1,
  "title": "The Alchemist",
  "author": "Paulo Coelho"
}
```

## API Endpoints

### Get All Books
- Method: GET
- URL: `/books`

### Add a New Book
- Method: POST
- URL: `/books`

Request Body:
```json
{
  "title": "Clean Code",
  "author": "Robert C. Martin"
}
```

### Update a Book
- Method: PUT
- URL: `/books/:id`

Request Body:
```json
{
  "title": "Updated Title",
  "author": "Updated Author"
}
```

### Delete a Book
- Method: DELETE
- URL: `/books/:id`

## Testing

Use Postman to test all endpoints:
- GET /books
- POST /books
- PUT /books/:id
- DELETE /books/:id

## Technologies Used

- Node.js
- Express.js
