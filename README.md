﻿# crud-test-junior-dotnet

Please read each note very carefully!
Feel free to add/change the project structure to a clean architecture to your view.

If you are not able to work on the FrontEnd project, you can add a Swagger UI
in a new Front project.

Create a simple CRUD application with .NET that implements the below model:
```
Customer {
	FirstName
	LastName
	DateOfBirth
	PhoneNumber
	Email
}
```

### Validations

- During Create; validate the phone number to be a valid *mobile* number only. you can use any lib for that or implement it yourself.

- A Valid email must be checked before submitting the form.

- Customers must be unique in the database: By `Firstname`, `Lastname`, and `DateOfBirth`.

- Email must be unique in the database.


### Storage

- Store the phone number in a database with minimized space storage (choose `varchar`/`string`, or `ulong` whichever store less space).

- Please use SQLServer to store data.


### Delivery
- Please clone this repository in a new GitHub repository in private mode and share with ID: `MohammadMobasher` in private mode on github.com, make sure you do not erase my commits and then create a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) (code review).



## Nice to do:
- Blazor Web.
- Docker-compose project that loads database service automatically which `docker-compose up`


