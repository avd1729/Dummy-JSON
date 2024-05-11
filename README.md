# Dummy JSON

This is a simple microservices website that allows users to retrieve recipes and products from different microservices.

## Features

- **Retrieve Recipes:** Users can fetch recipes from the Recipes microservice by clicking the "Get Recipes" button.
- **Retrieve Products:** Users can fetch products from the Products microservice by clicking the "Get Products" button.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- Flask
- Requests (if not using Flask to make requests)

## Installation

1. Clone the repository:

   ```bash
   git clone <https://github.com/avd1729/Dummy-JSON>
   ```

2. Navigate to the project directory:

   ```bash
   cd Dummy-JSON
   ```

3. Build the Docker image:

   ```bash
   docker build -t microservices-website .
   ```

4. Run the Docker container:

   ```bash
   docker run -p 5002:5002 microservices-website
   ```
5. Ensure the Recipes microservice is running. If not, clone the repository and follow the instructions in its README file to start the service.

   Repository URL: [Recipes Microservice](https://github.com/avd1729/Recipe-Microservice)

6. Ensure the Products microservice is running. If not, clone the repository and follow the instructions in its README file to start the service.

   Repository URL: [Products Microservice](https://github.com/avd1729/Product-Microservice)

## Usage

1. Open your web browser and navigate to [http://localhost:5002/](http://localhost:5002/).

2. Click the "Get Recipes" button to retrieve recipes from the Recipes microservice.

3. Click the "Get Products" button to retrieve products from the Products microservice.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the [Apache 2.0](LICENSE).
