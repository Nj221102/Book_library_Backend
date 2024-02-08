# Book API

This project provides APIs to manage books. It includes functionalities to retrieve all books, filter books by query parameters, fetch book details, and get unique lists of authors and countries.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Set up MongoDB:

    Make sure you have MongoDB installed and running locally or provide the MongoDB connection URI in the environment variable `MONGODB_URI`.

4. Start the server:

    ```bash
    npm start
    ```

## Usage

### API Endpoints

1. **GET /api/all-books**
   
   Retrieve all unique books.

2. **GET /api/books**
   
   Retrieve books based on query parameters. Supported query parameters include `title`, `country`, `year`, `author`, `language`, `pages`.

3. **GET /api/book/details**
   
   Retrieve details of a specific book by title.

4. **GET /api/authors**
   
   Retrieve a unique list of authors.

5. **GET /api/countries**
   
   Retrieve a unique list of countries.

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
