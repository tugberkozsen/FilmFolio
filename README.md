# FilmFolio 🎬

FilmFolio is a comprehensive movie library and management application built with **ASP.NET Core 7 MVC** and **Entity Framework Core**. The project follows the **Repository Pattern** to ensure a clean, maintainable, and scalable architecture.

## 🚀 Features

* **User Authentication:** Secure login, registration, and email confirmation powered by ASP.NET Core Identity.
* **Movie & Genre Management:** Structured relational database design for managing movies and their associated genres.
* **User Interactions:** * Users can add movies to their Favorites list.
    * Integrated Comment system for user reviews and discussions.
* **Architecture:** Clean separation of data access using the Repository Pattern (`IMovieRepository`, `IMovieGenreRepository`, `IFavoriteRepository`, `ICommentRepository`).
* **Dependency Injection:** Built-in DI container utilized for all repositories and services.

## 🛠️ Technologies Used

* **Framework:** .NET 7.0 
* **Web:** ASP.NET Core MVC & Razor Pages
* **ORM:** Entity Framework Core 7.0.13
* **Database:** SQL Server
* **Security:** ASP.NET Core Identity (with UI)
* **Frontend:** HTML5, CSS3, Bootstrap 5, jQuery

## ⚙️ Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites
* [.NET 7.0 SDK](https://dotnet.microsoft.com/download/dotnet/7.0)
* SQL Server (Express or Developer edition)
* Visual Studio 2022 (Recommended)

### Installation

1. **Clone the repo**
   ```sh
   git clone [https://github.com/tugberkozsen/FilmFolio.git](https://github.com/tugberkozsen/FilmFolio.git)
