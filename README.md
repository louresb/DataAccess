# Data Access

[![licence mit](https://img.shields.io/badge/licence-MIT-blue.svg)](https://github.com/louresb/DataAccess/blob/main/LICENSE)
![Development Status Badge](https://img.shields.io/badge/Status-Concluded-green)

This is a simple CRUD project for an e-learning platform, showcasing data access using Dapper in C#. 

## Database Setup

The scripts required to run this project are available at the [Scripts](https://github.com/louresb/DataAccess/tree/main/Scripts) folder of this repository.

## Available Features

- `CreateCategory`: Creates a new category.
- `CreateManyCategory`: Creates multiple categories at once.
- `UpdateCategory`: Updates the title of an existing category.
- `DeleteCategory`: Deletes an existing category.
- `ListCategories`: Lists all categories.
- `GetCategory`: Gets a specific category by ID.
- `ExecuteProcedure`: Executes a stored procedure to delete a student.
- `ExecuteReadProcedure`: Executes a stored procedure to get courses by category.
- `ExecuteScalar`: Executes a query and returns a single value.
- `ReadView`: Reads data from a view called `vwCourses`.
- `OneToOne`: Performs a join between the `CareerItem` and `Course` tables with a one-to-one relationship.
- `OneToMany`: Performs a join between the `Career` and `CareerItem` tables with a one-to-many relationship.
- `QueryMutiple`: Executes multiple queries in a single call.
- `SelectIn`: Performs a query using the `IN` clause.
- `Like`: Performs a query using the `LIKE` clause.
- `Transaction`: Executes an operation within a transaction.

Make sure to comment/uncomment features to verify them.

## Learning resources

This project was created using [Balta.io](https://balta.io/)'s backend course. I recommend checking it out if you're interested in learning about .NET programming.

## License
[MIT License](https://github.com/louresb/DataAccess/blob/main/LICENSE) © [Bruno Loures](https://github.com/louresb)
