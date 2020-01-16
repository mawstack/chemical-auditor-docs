# Chemical Auditor - Website Description

The client for this app is SSS Strawberries at Lot 2 Rosedale Road Oakwood QLD 4670.

### Purpose

As a strawberry farm there would be use of chemicals to help with the growth of crops and control of pests. Every time a chemical is used on the farm, an audit trail is required. This application is designed so that chemical distributing farm workers can easily record such information - for instance windspeed/weather at distribution time, or quantity of distributed chemicals. Thereafter, such day-to-day records can be compiled to produce audit reports, comprising a designated timeframes' collection of reports, and produced either at the users request, or at a designated timed interval (for example, via a monthly email). Thus the purpose is to enable workers to track chemical usage and generate reports for auditing requirements.

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
- express - Back-end server
- express-session - session storage functionality
- connect-mongo - session data store functionaliy
- lodash - general helper methods 
- nodemon - Live-server monitoring
- React - Front-end view rendering & geolocation services
- Node - Database
- Heroku - deployment of webserver 
- MongoDB - User information & record storage
- Cloud Atlas - MongoDB hosting
- body-parser - simplified request bodies
- jest - testing
- cors - cross origin request support
- mongoose - create model schemas and query mongoDB
- dotenv - access .env variables
- mongoose-bcrypt - encrypt passwords in mongoDB
- celebrate - user input validation
- jwt - json web token functionality
- passport - authenticate requests
- axios - make promise AJAX requests
- cron - automatic monthly reports
- react-dom - connects React to the browser DOM
- react-router-dom - enables React single-page refresh routing
- react-redux - connect React and Redux
- redux - internal data functionality
- Material UI - styling framework
- Open Weather - api for weather information
- Climacell - api for weather information
