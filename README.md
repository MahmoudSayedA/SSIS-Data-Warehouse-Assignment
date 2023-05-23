# SSIS-Data-Warehouse-Assignment

This is a repository for the SSIS Data Warehouse Assignment for the third year students of the Faculty of Computers and Artificial Intelligence at Cairo University.

## Description
This assignment consists of three questions that required solving using SQL Server Integration Services (SSIS). The questions cover different aspects of data integration, including consuming a REST API, implementing a Slowly Changing Dimension (SCD) type 6, and loading data to a table using versioning.

## Requirements
To run this project, you will need:

- SQL Server 2016 or later
- SQL Server Data Tools (SSDT) for Visual Studio
- A REST API to consume data from (for question 1)

## Files
This repository contains the following files:

- Problem1: that contains SSIS package for consuming a REST API and loading data to a database table.
- Problem2: that contains SSIS package for implementing SCD type 6 for a table.
- Problem3: that contains SSIS package for loading data to a table using versioning.
- assignment2.pdf: assignment description
- images: for images provided
- README.md: This file.

## Usage
- Clone the repository to your local machine.
- Open the SQL Server Data Tools (SSDT) for Visual Studio.
- Open the SSIS packages (Question1.dtsx, Question2.dtsx, Question3.dtsx) from the Solution Explorer.
- **Update the connection managers** in the packages to match your database server and credentials.
- If applicable, update the REST API endpoint and authentication in the Question1.dtsx package.
- Execute
- Verify that the data is loaded correctly in the database tables.

## Contributing
This project is not open for contributions since it is an assignment. However, if you have any questions or feedback, feel free to contact with us

Authors
This assignment was completed by [Mahmoud Sayed](https://github.com/MahmoudSayedA/) and [Salma Mohamed](https://github.com/salma-mohamed-37) for the SSIS Data Warehouse course at Cairo University.

License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
