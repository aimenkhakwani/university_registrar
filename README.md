# University Registration

#### _9-27-16_

#### By _**Martin Cartledge &amp; Aimen Khakwani**_

## Description

A web app for a university registrar to register courses and students to a university. Demonstrates MySQL many-to-many relationship, and uses join statements. The registrar can add students and courses, as well as delete and update them (CRUD). The web app displays individual students with all the courses they are enrolled in, as well as an option to add a course to the student course. The same can be done with a course (add a student in the course or view all students enrolled in a particular course). 

<img src="/web/screenshot.png" alt="a screenshot of the site">

## Setup/Installation Requirements

* Clone the repository
* Using the command line, navigate to the project's root directory
* Install dependencies by running $ composer install
* Start MySQL by running the command $ /Applications/MAMP/Library/bin/mysql --host=localhost -uroot -proot
* Start Apache by running the command $ apachectl start
* Import the MySQL file from localhost:8080/phpmyadmin/
* Navigate to the /web directory and start a local server with $ php -S localhost:8000
* Open a browser and go to the address http://localhost:8000 to view the application

## Known Bugs

_None yet_

## Support and contact details

_Martin Cartledge: martincartledge@icloud.com_

## Technologies Used

_HTML,
CSS,
JS,
PHP,
Silex,
Twig,
PHPUnit,
MySQL_

### License

*This webpage is licensed under the MIT license.*

Copyright (c) 2016 **_Martin Cartledge &amp; Aimen Khakwani_**
