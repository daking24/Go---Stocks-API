
# Go Stocks
A simple RESTful API built with Go, Gin, and Mux for managing a stock's resources.

## Getting Started
**Prerequisites**
* Go - Install the latest version available from the official website
* Git - To clone the repository

## Installing
1. Clone the repository:

```console
git clone https://github.com/daking24/Go---Stocks-API.git
cd go-postgres-yt
```
2. Install the required packages:
Copy code
```console
go get -v
```
3. Run the application:
```console
go run main.go
```

## API Endpoints

* Endpoint: `GET /api/stock`
**Fetch all Stocks**

* Endpoint: `POST /api/new-stock`
**Create a Stock**

* Endpoint: `GET /api/stock/{id}`
**Get a Stock by ID**

* Endpoint: `PUT /api/stock/{id}`
**Update a Stock by ID**

* Endpoint: `DELETE /api/delete-stock/{bookId}`
**Delete a Stock by ID**

## Contributing
Feel free to submit a pull request or open an issue to contribute to the project. Make sure to include a detailed description of the changes and any relevant context.

## License
This project is open source and licensed under the [MIT License](https://opensource.org/license/mit).

## Contact
If you have any questions, feel free to reach out to the maintainer at [kingdavidao11@gmail.com](mailto:kingdavidao11@gmail.com).