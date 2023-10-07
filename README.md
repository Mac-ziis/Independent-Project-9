# _Eau Claire's Salon_

#### By _**Mac Granger**_

#### _This is an MVC web application for Eau Claire's Salon that helps to manage stylists and their clients._

## Technologies Used

* _C#_
* _ASP.NET Core MVC_
* _Razor Pages_
* _Visual Studio Code_
* _Github_

## Description

_This is an MVC web application for Eau Claire's Salon that helps to manage stylists and their clients. You will need to add a new stylist before you can add their clients, each client will pertain to one stylist. To add a client, select the stylist from the dropdown menu, add the description of the client, and then select "Add Client". This application will help Eau Claire keep track of her stylists and all of their clients. You can add, delete, and alter stylists and their clients._

## Setup/Installation Requirements

-- Note: An installation of the .NET SDK is required in order to run this application locally. [See Here](https://dotnet.microsoft.com/en-us/) for installation.
* _Clone this repo._
* _Open your shell (e.g., Terminal or GitBash) and navigate to this project's directory called "HairSalon.Solution"._
* _Create a file named `appsettings.json`: `$ touch appsettings.json`_
* _Within `appsettings.json` add the following code, replacing the `uid` and `pwd` values with your own username and password for MySQL._
```json
    {
      "ConnectionStrings": {
          "DefaultConnection": "Server=localhost;Port=3306;database=ryans_todo_from_section3;uid=[YOUR-USERNAME];pwd=[YOUR-MYSQL-PASSWORD];"
      }
    }```
* _Set up the Database. Follow the instructions in the LearnHowToProgram.com lesson ["Creating a Test Database: Exporting and Importing Databases with MySQL Workbench"](https://www.learnhowtoprogram.com/c-and-net/database-basics/creating-a-test-database-exporting-and-importing-databases-with-mysql-workbench) to use the `mac_granger.sql` file located at the top level of this repo to create a new database in MySQL Workbench with the name `mac_granger`.
* _Navigate to the project directory: `$ cd HairSalon`_
* _Run `$ dotnet watch run` in the command line to start the project in development mode with a watcher._
* _Open the browser at: _https://localhost:5001_. If you cannot access localhost:5001 it is likely because you have not configured a .NET developer security certificate for HTTPS. To learn about this, review this lesson: [Redirecting to HTTPS and Issuing a Security Certificate](https://www.learnhowtoprogram.com/c-and-net/basic-web-applications/redirecting-to-https-and-issuing-a-security-certificate).
_


## Known Bugs

* _No known bugs._

## License

Copyright (c) 2023 Mac Granger

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
