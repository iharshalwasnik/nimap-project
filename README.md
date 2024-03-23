# Nimap Application

This is a Spring Boot application implementing CRUD operations for categories and products.

## Requirements

- Java 11 or higher
- Maven
- MySQL database

## Setup

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/nimap.git
    ```

2. Navigate to the project directory:

    ```bash
    cd nimap
    ```

3. Build the project:

    ```bash
    mvn clean install
    ```

4. Run the application:

    ```bash
    mvn spring-boot:run
    ```

## Endpoints

### Categories

- **GET /api/categories**: Retrieve all categories.
- **POST /api/categories**: Create a new category.
- **GET /api/categories/{id}**: Retrieve a category by ID.
- **PUT /api/categories/{id}**: Update a category by ID.
- **DELETE /api/categories/{id}**: Delete a category by ID.

### Products

- **GET /api/products**: Retrieve all products.
- **POST /api/products**: Create a new product.
- **GET /api/products/{id}**: Retrieve a product by ID.
- **PUT /api/products/{id}**: Update a product by ID.
- **DELETE /api/products/{id}**: Delete a product by ID.

## Database Configuration

- The application uses MySQL database. Configure the database connection in the `application.properties` file.

## Technologies Used

- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for any improvements or features you'd like to see.

## License

This project is licensed under the [MIT License](LICENSE).
