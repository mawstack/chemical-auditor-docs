#Chemical Auditor - Website Description
Every time a chemical is used on the farm, an audit trail is required. This application is designed so that chemical distributing farm workers can easily record such informatiom - for instance windspeed/weather at distribution time, or quantity of distributed chemicals. Thereafter, such day-to-day records can be compiled to produce audit reports, comprising a designated timeframes' collection of reports, and produced either at the users request, or at a designated timed interval (for example, via a monthly email).

##Features
- Login system distinguishing regular employee/administrator permissions
- Report generation, when requested/at timed intervals
- Chemical Tracking information - Weather, GPS/manual location, time/date, chemical information, reason for use and amount used etc.
- Attach photographs to reports
- Secure storage for all information

##Flex-goal Features
- Admins can approve regular employee entries/edits
- Progressive Web App

##Target Audience
- Farm employees - creating individual records in the field
- Farm managers - generating full reports in the office, comprising a designated timeframes' worth of employee records

##Tech Stack
- AWS - Image upload storage
- MongoDB - User information & record storage
- Express - Back-end server
- React - Front-end view rendering & geolocation services
- Node - Database
- Various APIs/Packages
