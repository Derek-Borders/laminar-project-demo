# laminar Point of Sale 
Cloud based POS Solution *(Proof of Concept)*

## Technology & Tools  


<img src="./icons/html5.svg" alt="HTML5"  width="5%" />
<img src="./icons/css3.svg" alt="CSS 3"  width="5%" />
<img src="./icons/javascript.svg" alt="JavaScript" width="5%" />
<img src="./icons/python.svg" alt="Python" width="5%" />
<img src="./icons/django.svg" alt="Django" width="5%" />
<img src="./icons/sqlite.svg" alt="SQLite" width="5%" />
<img src="./icons/mariadb.svg" alt="MariaDB" width="5%" />
<img src="./icons/php.svg" alt="php" width="5%" />
<img src="./icons/docker.svg" alt="Docker" width="5%" />
<img src="./icons/googlecloud.svg" alt="Google Cloud Platform" width="5%" />
<img src="./icons/vscode.svg"  alt="Visual Studio Code" width="5%" />
<img src="./icons/git.svg" alt="git" width="5%" />
<img src="./icons/github.svg" alt="GitHub" width="5%" />

##  Project Overview & Demo
This repository serves as a high level overview of the Laminar cloud point of sale proof of concept (PoC).  

Laminar was inspired by a variety of restaurant Point of Sale (PoS) systems used by team members over the years; notably [NCR's Aloha](https://www.ncr.com/restaurants/aloha-restaurant-pos-system) for its ubiquity, scale, and dated UI/UX and [Toast](https://pos.toasttab.com/) for its sleek, modern UI, excellent UX, and cloud-based nature. 

The goal of the project was to design and build a proof of concept for a complex but well known type of enterprise software.

## Timeline 
Laminar was developed in three iterations with different focuses. Each phase was part of a group or partnership project for one of three courses: Introduction to Databases, Web Programming Fundamentals, and Software Engineering. 

Version 0.1 of the PoC, a four-person group project for an Introduction to Databases course, focused on designing and building the underlying database. The design used non-UML entity relationship modeling and flow charts. The database was built with MariaDB, and connected to the front end with PHP. The front end for this proof of concept was only parially functional. More than wireframes, but less than a fully functioning demo. The underlying database was more fully functional with a robust set of example menu, submenu, item, and employee data and some limited transaction data. 

v0.2, a partner project for a Web Programming Fundamentals course, focused on the front end web design, containerization, cloud hosting, and backend implementation using a new framework/stack. This involved rebuilding much of the previous version from scratch using a Python and Django with SQLite as the default DBMS under the hood. This version had much more robust HTML and CSS including a dark mode and a variety of minor accessability and user experience improvements. v0.2 was also containerized with Docker and hosted on Google Cloud Platform. This iteration had fewer pages than the first, but the functionality of these pages was more complete. Ehe example data was left out, to be created using the proof of concept interface itself.

v0.3, (or perhaps v0.2.1) a six-person group project for a Software Engineering Course, focused primarily on the design process. Most of the work for this phase involved formalizing, and fleshing out Laminar's design while upgrading it to be UML 2.5 compliant. This was accomplished using Agile principles and methodologies, primarily Scrum and Kanban (using Trello). Despite the focus being on design, some functionality was also added to the v0.2 PoC, which was used as the starting point for this phase.

As of now, v0.3 is still just a proof of concept, far from a full prototype of the enterprise software system it could theoretically become. Currently, there are no plans to continue deveolpment or to attempt to bring the project into an already crowded marketplace.

## TODO
- ~~Quick google for inspiration~~
- Create gifs of features (Reilly)
- Add relevant text from reports (Derek)
- ~~Add features sub-level bullets~~ (Derek)
- Collage (Reilly)
  

## Features  

- Phrasing?
  - Add/Edit/Remove X ?
  - Add, Edit & Remove X ?
  - Manage X ?
  - Maintain X ?
  - X ? (no prefix)

<br />  

#### Usage  

- Labor Management  
  - Employees 
  - Employee Roles
  - Employee Access Levels
  - Shifts
- Item Management
  - Menu items
- Menu/Submenu Management
  - Menu Groups (containing submenus)
  - Submenus (containing Items)
- Order Management
  - Tabs (groups of tickets)
  - Tickets (division of tabs)
  - Orders (item groups sent for prep)
  - Payments 
- Login & Authentication
- Shift Tracking
- Sales Tracking

#### Interface  
- Browser-Friendly Web App 
  - (no proprietary tech required)
- Dark Mode Option

### Labor Management  

Employee
*insert image/gif*

Role
*insert image/gif*

Access Level
*insert image/gif*


Quick comment.
*insert image/gif*

### Item Management  

Items
*insert image/gif*

### Menu Management

Submenus + Contents
*insert image/gif*



### Order Management

New Table / Tickets
*insert image/gif*

Item Selection
*insert image/gif*

Payments
*insert image/gif*

## Design Overview

*Show off UML stuff here*

## Backlog 
- Features
  - Labor
    - Clock in/out 
    - Declare tips
  - Items
    - Mods/recipes
  - Menus/Submenus
    - Multi-menu functionality
  - Modifier System
  - Orders
    - Send/Hold Order
    - Chit Printing
  - Reports
    - Inventory
    - Product Mix
    - Sales
    - Labor
    - Payroll
  - Inventory Management
  - Payment Processing (EoD)
    - Bank Deposits
    - Electronic Payments
- UI
  - Improve Responsiveness
  - Fix Dark Mode
  - Implement Drag & Drop