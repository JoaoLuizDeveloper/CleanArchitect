CleanArchitect
A personal project by João Luiz implementing Clean Architecture principles in a .NET application. The solution is organized into distinct layers to promote separation of concerns and maintainability.

📁 Project Structure
CleanArchitec.API: Entry point of the application, exposing RESTful endpoints.

CleanArchitec.Application: Contains application logic, including use cases and service interfaces.

CleanArchitec.Core: Holds domain entities and interfaces, representing the business rules.

CleanArchitec.Infrastructure: Implements data access and external service integrations.

CleanArchitec.sln: Visual Studio solution file.

🛠️ Technologies Used
.NET Core

Entity Framework Core

Clean Architecture

RESTful API

🚀 Getting Started
Clone the repository:

git clone https://github.com/JoaoLuizDeveloper/CleanArchitect.git
cd CleanArchitect
Set up the database:

Ensure you have a SQL Server instance running.

Update the connection string in appsettings.json within the CleanArchitec.API project.

Apply migrations and update the database:

dotnet ef database update --project CleanArchitec.Infrastructure --startup-project CleanArchitec.API
Run the application:

Navigate to the CleanArchitec.API project directory.

Run the application:

dotnet run
The API will be available at http://localhost:5000.

📄 License
This project is licensed under the MIT License.
