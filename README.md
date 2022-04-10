# _Factory Records C#_

#### By _**Chris Nakayama**_

#### _A Factory APP ._

## Technologies Used

* _C#_
* _.NET 5.0_
* _ASP.NET Core_
* _CSS_
* _Bootstrap_
* _Razor View Engine_
* _Entity Framework Core_

## Description

_This simple web application shows a many to many relationship with a database in SQL. Users can then associate Engineers with different machines they are able to repair._

## Setup Instructions

* _Open your terminal and navigate to the folder you'd like to download the files into._
* _Run the command below_
> git clone https://github.com/ChrisNakayama/FactoryRecords
* _Download [MySQL Workbench](https://www.mysql.com/products/workbench/) and use it to create a local instance and an associated password._
* Within the directory ~/Factory, create a file named appsettings.json and input the lines of code bellow.
> {
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=factory;uid=root;pwd=epicodus;"
  }
}
  * Replace [YOUR-PASSWORD] with the password you created within MySQL Workbench and make sure the port matches your own.
* _Navigate to ~/Factory in your terminal._
* _Run the commands below_
>dotnet tool install --global dotnet-ef --version 3.0.0

>dotnet add package Microsoft.EntityFrameworkCore.Design -v 5.0.0

>dotnet ef database update

>dotnet build

>dotnet run

* _Copy and paste the local host URL provided in the terminal into a web browser and enjoy!_
## Known Bugs

* _No known bugs at this time._

## License

Copyright (c) _03/31/2022_ _by Chris Nakayama_


_Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:_

_The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software._

_THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE._