# Timestamp Microservice

This Node.js project serves as a simple API that provides information about dates. It includes two API endpoints, one for a specified date and another for the current date. The project utilizes the Express.js framework for creating the API.

## Getting Started

Follow the instructions below to set up and run the project on your local machine.

### Prerequisites

Make sure you have Node.js and npm (Node Package Manager) installed on your machine.

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <project_directory>
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

### Running the Application

Start the Node.js application:

```bash
npm start
```

The application will be running on the specified port, and you can access it in your web browser or through tools like [Postman](https://www.postman.com/) for API testing.

## Project Structure

- **index.js:** The main file containing the Node.js application code.
- **public/:** Contains static files for the project (e.g., HTML, CSS).

## API Endpoints

### 1. Get information about a specified date

- **Endpoint:**
  ```
  GET /api/:date
  ```

- **Parameters:**
  - `:date` (optional): A parameter representing the date. If not provided, it defaults to the current date.

- **Response:**
  - Returns JSON with Unix timestamp and UTC string representation of the specified date.
  - If the provided date is invalid, it returns a JSON object with an error message.

### 2. Get information about the current date

- **Endpoint:**
  ```
  GET /api
  ```

- **Response:**
  - Returns JSON with Unix timestamp and UTC string representation of the current date.

## Additional Information

- **CORS:** Cross-Origin Resource Sharing is enabled to allow remote testing of the API by FCC (FreeCodeCamp).
- **Static Files:** The project serves static files from the "public" directory.

## Contributing

Feel free to contribute to this project by submitting issues or pull requests. Your contributions are highly appreciated!

## License

This project is licensed under the [MIT License](LICENSE).
