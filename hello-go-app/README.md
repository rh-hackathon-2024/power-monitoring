# README.md

# Hello Go App

This is a simple Go application that prints "Hello, World!" to the console. 

## Getting Started

To build and run the application, follow these steps:

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd hello-go-app
   ```

2. **Build the application:**
   ```
   go build -o hello cmd/main.go
   ```

3. **Run the application:**
   ```
   ./hello
   ```

## Containerization

To build and run the application in a Docker container, use the following commands:

1. **Build the Docker image:**
   ```
   docker build -t hello-go-app .
   ```

2. **Run the Docker container:**
   ```
   docker run hello-go-app
   ```

## License

This project is licensed under the MIT License.