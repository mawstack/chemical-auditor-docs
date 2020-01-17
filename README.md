# Chemical Auditor Documentation

## Website Description

Client: SSS Strawberries
Address: Lot 2 Rosedale Road Oakwood QLD 4670
Contact Name: Ijan Kruizinga

### Purpose

Due to the use of herbicides and pesticides on farms, and the resulting environmental impacts, audit trails are kept to ensure quality assurance requirements for pre-harvest chemical applications. The purpose of our application is to allow chemical-distributing farm workers to easily record all relevant information, moving the farm towards more efficient and environmentally friendly (fully digital) record keeping. The application will also allow the generation of reports for use by farm managers in auditing meetings.

The benefits this application could bring to the farm include a streamlining of the record-keeping process, addition of photographic evidence, as well as increased transparency, efficiency and data security.

### Features

- Login system distinguishing regular employee/administrator permissions
- Report generation, when requested/at timed intervals
- Chemical Tracking information - Weather, GPS/manual location, time/date, chemical information, reason for use and amount used etc.
- Attach photographs to reports
- Secure storage for all information

#### Flex-goal Features

  - Admins can approve regular employee entries/edits
  - Progressive Web App

### Target Audience

- Farm employees - creating individual records in the field
- Farm managers - generating full reports in the office, comprising a designated timeframes' worth of employee records

### Tech Stack

- AWS - Image upload storage
- MongoDB - User information & record storage
- Express.js - Back-end server
- Express-session - session storage functionality
- Connect-mongo - session data store functionality
- Lodash - Various general helper methods
- Nodemon - Live-server monitoring
- React - Front-end view rendering & geo-location services
- Node.js - Javascript environment to run backend
- Heroku - Deployment of web server
- MongoDB Atlas - MongoDB cloud hosting
- Body-parser - Simplified request bodies
- Jest - Testing
- CORS - Cross origin request support
- Mongoose - Create model schemas and query MongoDB
- Dotenv - Access .env variables
- Mongoose-bcrypt - Encrypt passwords in MongoDB
- Celebrate - User input validation
- JWT - JSON web token functionality
- Passport - Authenticate requests
- Axios - Make promise AJAX requests
- Cron - Automatic monthly reports/'Cron jobs'
- React-dom - Connects React to the browser DOM
- React-router-dom - Enables React single-page refresh routing
- React-redux - Connect React and Redux
- Redux - Internal data functionality
- Material UI - Styling framework
- Open Weather - API for weather information
- Climacell - API for weather information

## Data flow diagram

![data flow diagram](./Data_Flow.png)

## Application Architecture Diagram

![application architecture diagram](./Application_Architecture_Diagram.png)

## User Stories

### As a seasonal worker, I need to easily understand and use the application with little extra training.

- As Hamish the seasonal worker, I need to be able to easily approach and understand the application, ensuring I can fulfil my job roles with little extra training.
- As John the seasonal worker, I would like to have a logical layout with intuitive logos, to enable me to fulfil my role without a complicated use of the English language.

### As a full-time employee, I need to be able to review information quickly and plan my daily work efficiently.

- As full-time employee Garret, I would like to quickly attain weather information from the application to plan my daily work schedule.
- As Garret, I need to have quick access to recent entries to reduce double-handling and ensure my work is completed.
- As full-time employee Rebecca, I would like a more efficient means of creating records than I have at present, cutting down office admin and ensuring accuracy during busy periods.
- As Rebecca, I would like to be able to receive feedback from my managers regarding my record entries.

### As a farm manager, I need to be able to keep track of data entries, and easily generate reports to meet auditing requirements.

- As Vicky the farm manager, I need to be able to easily generate an up-to-date reports as required by auditors.
- As Vicky, I need to be able to view recent entries, and view each individual entries details if required.
- As Vicky, I need to be able to edit reports if data is entered incorrectly.
- As Michael, I need to be able to leave feedback and notes within entries if required.
- ensure sensitive data (trade data) is stored safely & securely
- As Michael, I want to ensure the farms sensitive trade data is stored safely and securely.

### As an auditor, I need reports to be legible, easily understood, and to adhere to the legal requirements of the audit.

- As an auditor, I need to be able to easily read and understand the new format of audit reports, with them following the current design pattern to ensure confusion is minimized.
- As an auditor, I need to be sure all legal requirements are met regarding information integrity.

## Wireframes

### Dashboard

![dashboard mobile wireframe](./Wireframes/dashboard-mobile.png)
![dashboard tablet wireframe](./Wireframes/dashboard-tablet.png)
![dashboard desktop wireframe](./Wireframes/dashboard-desk.png)

### Login

![login mobile wireframe](./Wireframes/login-mobile.png)
![login tablet wireframe](./Wireframes/login-tablet.png)
![login desktop wireframe](./Wireframes/login-desk.png)

### New Entry

![new entry page mobile wireframe](./Wireframes/newEntry-mobile.png)
![new entry page tablet wireframe](./Wireframes/newEntry-tablet.png)
![new entry page desktop wireframe](./Wireframes/newEntry-desk.png)

### View Entry

![view entry page mobile wireframe](./Wireframes/viewEntry-mobile.png)
![view entry page tablet wireframe](./Wireframes/viewEntry-tablet.png)
![view entry page desktop wireframe](./Wireframes/viewEntry-desk.png)

## Trello board screenshots

![trello board screenshot 1](./Screenshots/1.PNG)
![trello board screenshot 2](./Screenshots/2.PNG)
![trello board screenshot 3](./Screenshots/3.PNG)
![trello board screenshot 4](./Screenshots/4.PNG)