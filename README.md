ASP.NET Core Microservice with Web API CRUD Operations on a MongoDB database [Clean Architecture]
Welcome to our ASP.NET Core Microservice tutorial where we will guide you through building a Microservice that performs CRUD operations on a MongoDB database using a Web API. This Microservice is designed following Clean Architecture principles and is intended to be a part of a drone pizza delivery application.
Getting Started
To get started with this project, follow these steps:
Clone the repository to your local machine.
Ensure you have the necessary prerequisites installed (ASP.NET Core, MongoDB).
Update the MongoDB connection string in the appsettings.json file.
Build and run the project.
Project Structure
The project follows a Clean Architecture approach, with the following main components:
Application: Contains the application logic and interfaces.
Domain: Contains the domain models and business logic.
Infrastructure: Contains the implementation of data access and external services.
WebAPI: Contains the controllers and API endpoints.
API Endpoints
The Web API exposes the following CRUD operations:
GET /api/{entity}: Retrieve all {entity}.
GET /api/{entity}/{id}: Retrieve a specific {entity} by ID.
POST /api/{entity}: Create a new {entity}.
PUT /api/{entity}/{id}: Update an existing {entity} by ID.
DELETE /api/{entity}/{id}: Delete a {entity} by ID.
Contributing
We welcome contributions to this project. If you have any suggestions, improvements, or bug fixes, feel free to submit a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for more details.
Thank you for checking out our ASP.NET Core Microservice tutorial. Happy coding! 🚀
