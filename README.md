# Nginx Crash Course

This project is a simple Node.js application that serves a static HTML file. It is designed to demonstrate load balancing with NGINX.

## Project Structure

```
nginx-demo/
├── images/
├── index.html
├── package.json
├── README.md
└── server.js
```

## Prerequisites

- Node.js installed on your machine
- NPM (Node Package Manager) installed

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/nginx-demo.git
    cd nginx-demo
    ```

2. Install the dependencies:
    ```sh
    npm install
    ```

## Running the Application

Start the server by running:
```sh
npm start
```

The application will be available at `http://localhost:3000`.

## Environment Variables

- `APP_NAME`: The name of the application (default: "Nginx Demo")

## Usage

- The server serves static files from the `images` directory.
- The root URL (`/`) serves the `index.html` file.

## License

This project is licensed under the MIT License.
