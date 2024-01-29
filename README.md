## This application consists of:

*   Template pages with Angular 17 and TypeScript
*   RESTful API Backend using ASP.NET Core 8 Web API
*   Database using Entity Framework Core
*   Authentication/Authorization based on OIDC/OAuth2 and ASP.NET Core Identity
*   API Documentation using Swagger
*   Angular CLI for managing client-side libraries
*   Theming using Bootstrap 5

## You get the benefits of:

*   A complete backend and frontend project structure to build on, with login, user and permission-based role management already integrated
*   Data Access Layer built with the Repository and Unit of Work Pattern
*   Code First Database
*   A RESTful API Design
*   Angular Directives Guidance
*   Angular Pipes Guidance
*   Angular Animations Guidance
*   Angular Services
*   Dialog and Notification Services
*   Configuration Page and Configuration Service
*   Integrated Internationalization
*   Theming with SASS
*   Ready-to-use email API
*   Handling Access and Refresh Tokens with WebStorage (Bearer authentication)
*   CRUD APIs
*   Responsive Design
*   Etc.


## Installation Notes

*   When creating a new project please wait for all dependencies to be restored; "dotnet restore" for asp.net project & "npm install" for angular project.
    When using VisualStudio this is automatic, check the output window or status bar to know that the package/dependencies restore process is complete before launching your program for the first time.
*   If you get any errors, consider running manually the steps to build the project and note where the errors occur.
    Open command prompt and do the below steps:  
    1. run 'dotnet restore' from the two project folders - Restore nuget packages
	2. run 'npm install' from the project with package.json - Restore npm packages
	3. Try running the application again - Test to make sure it all works
*	When running the client(angular) project on a different address/domain from the backend, configure the baseUrl of the client to match that of the server.
	You do this from environment.ts in the ClientApp/Angular project.
	Example: baseUrl: "http://yourbackendserver.com" OR baseUrl: "http://localhost:5050"


## Login

LOGIN WITH USERNAME OR EMAIL ADDRESS
> * **Default Administrator Account**
>   * Username: admin
>   * Email:    admin@admin.com
>   * Password: Admin@123
> * **Default Standard Account**
>   * Username: user
>   * Email:    user@user.com
>   * Password: User@123
