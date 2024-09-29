# Movies CRUD Application in Go

This is a basic Movies CRUD (Create, Read, Update, Delete) application built using Golang and the `gorilla/mux` package for routing.

## Features

- **Create a Movie**: Add a new movie to the list.
- **Read Movies**: Retrieve a list of all movies or a specific movie by ID.
- **Update a Movie**: Modify the details of an existing movie.
- **Delete a Movie**: Remove a movie from the list.

## Endpoints

- **GET /movies**: Get the list of all movies.
- **GET /movies/{id}**: Get details of a specific movie by its ID.
- **POST /movies**: Create a new movie by sending a JSON body.
- **PUT /movies/{id}**: Update an existing movie by its ID.
- **DELETE /movies/{id}**: Delete a movie by its ID.

## Technologies Used

- [Golang](https://golang.org/) - The programming language used for the project.
- [gorilla/mux](https://github.com/gorilla/mux) - A powerful URL router and dispatcher for Golang.

## Setup and Running the Project

```bash
# 1. Install Golang
# Make sure you have Golang installed on your machine. You can download it from https://golang.org/dl/

# 2. Clone the Repository
git clone https://github.com/yourusername/movies-crud-go.git

# 3. Navigate to the Project Directory
cd movies-crud-go

# 4. Install Dependencies
# You need to install the gorilla/mux package
go get -u github.com/gorilla/mux

# 5. Run the Application
go run main.go

# 6. Access the API
# The API will be available at http://localhost:8000
```
