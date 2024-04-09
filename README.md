**MvcMovie**

This repository contains a simple ASP.NET Core MVC application developed by following the tutorial provided by Microsoft. The tutorial can be found [here](https://learn.microsoft.com/en-us/aspnet/core/tutorials/first-mvc-app/start-mvc?view=aspnetcore-8.0&tabs=visual-studio).

### Overview
The application allows users to manage a collection of movies. Users can view, add, edit, and delete movies from the collection.

### Technologies Used
- ASP.NET Core MVC
- Entity Framework Core
- C#
- HTML
- CSS

### Project Structure
- **Models**: Contains the data models used in the application.
- **Controllers**: Contains the controller classes that handle user requests.
- **Views**: Contains the Razor views that generate HTML responses for users.
- **Data**: Contains the database context and migration files for Entity Framework Core.

### Running the Application
To run the application locally, follow these steps:
1. Clone this repository to your local machine.
2. Open the solution file (`MvcMovie.sln`) in Visual Studio.
3. Build the solution to restore NuGet packages and compile the project.
4. Set up a database using Entity Framework Core migrations. You can do this by opening the Package Manager Console and running `Update-Database` command.
5. Run the application by pressing `Ctrl + F5` or clicking on the "Start" button in Visual Studio.

### Functionality
- **View Movies**: Users can view a list of movies.
- **Search**: Users can search for movies by title.
- **Filter**: Users can filter movies by genre.
- **Add Movie**: Users can add new movies to the collection.
- **Edit Movie**: Users can edit existing movie details.
- **Delete Movie**: Users can delete movies from the collection.

### Additional Notes
- This application serves as a basic example of building a CRUD (Create, Read, Update, Delete) application using ASP.NET Core MVC and Entity Framework Core.
- Feel free to explore the codebase, experiment with changes, and extend the functionality as needed.

For any questions or issues, please refer to the [official documentation](https://learn.microsoft.com/en-us/aspnet/core/?view=aspnetcore-8.0) or open an issue in this repository.
