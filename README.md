# real_estate
## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Prerequisites](#prerequisites)
* [Installation](#installation)
* [Execution](#execution)
* [License](#license)

## General info
This project is designed to satisfy the following requirements : 
* Allows the user to upload files in csv format and update the database with the data from the files.
* Generate aggregate informations such as address of the asset,year of construction,total rent,vacany,walt etc..for the assets.

## Technologies
Project is creaeted with:
* Java 
* Spring Boot
* PostgreSQL 
* Swagger
* Maven
* Apache
* IDE : Eclipse

## Prerequisites
Before you continue, ensure you have met the following requirements:
* You have installed the latest version of Java,PostgreSQL.
* You are using a  Windows or Linux or Mac OS machine.

## Installation
* Download the real-estate.zip and extract the files to your local system.
* Open Eclipse IDE and choose File->Import->Maven->Existing Maven Project.
* Browse real-estate project where it has been extracted earlier.
* Wait for sometime,until eclipse builds the project.

## Execution
* Open PostgreSQL and create a database with the name testdb.
* Goto Eclipse IDE and run RealEstateApplication.
* Once the tomcat server has started.Open the swagger url - http://localhost:8080/swagger-ui.html in your favourite browser.
* There will be three controllers :
    i.  AssetController
    ii. ImportController
    iii.BasicErrorController
# Import Controller
* Allows the user to upload csv file.
* Click try it out.
* Choose files and click upload button.

# Assert Controller
* Returns certain information about the assets.
* Click try it out and execute.
* All the required information about the assets will be shown.
* If any information for a particular asset is needed,enter the Asset Reference (asset_ref) and click execute.

## License
MIT License

Copyright (c) [2020] [VigneshDhandapani]

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


