#Description
This is a movie management application built with ASP.NET Core MVC. The application allows users to view, create, edit, and delete movie records, as well as filter movies by genre, title, and release year.
Features Implemented

#Custom Application Title - Changed the app title to "[Your Name] Movies"
Seed Data - Added three favorite movies to the database
Custom Page Heading - Changed "Index" to "My Movies" on the main listing page
Year Filter - Added ability to filter movies by release year or newer
Improved Form Styling - Added padding to all form input elements for better readability

#Technologies Used

ASP.NET Core MVC
Entity Framework Core
C#
Razor Views
Bootstrap CSS
SQLite/SQL Server Database

#How to Run

Clone this repository
Navigate to the project directory
Run dotnet ef database update to create the database
Run dotnet run to start the application
Open your browser to https://localhost:5001 or the port shown in terminal

#Project Structure

Controllers/ - Contains the MoviesController with all CRUD operations
Models/ - Contains Movie and MovieGenreViewModel classes
Views/ - Contains Razor views for displaying movie data
Data/ - Contains the database context and seed data
wwwroot/css/ - Contains custom CSS styling
