Under the guidance of Jonas Schmedtmann's Node.js course, the Natours application was developed. It encompasses several key features and technologies:

**Features:**
1. Creating an API
2. Implementing MVC Architecture
3. User Authentication
4. Data Modeling
5. File Uploading
6. Browsing and booking nature tours
7. User account creation and management
8. Persistent login sessions using cookies
9. Detailed tour information display
10. Interactive maps for tour destinations
11. Tour reviews and ratings
12. Password reset functionality
13. Profile and password update
14. Profile picture uploading
15. Email service integration
16. Responsive design for various devices

**Technologies Used:**
- Node.js
- Express.js
- MongoDB
- Mongoose
- HTML
- CSS
- Pug (Template Engine)
- Nodemailer
- Mailtrap
- JSON Web Token (JWT)
- bcrypt
- Gmail

**Future Considerations:**
- Learning React for potential incorporation into the application.

**Setting Up Local Environment:**
To set up the Natours app locally:
1. Clone the repository from GitHub.
2. Install dependencies using `npm install`.
3. Configure environment variables by creating a `.env` file in the root directory and adding the necessary variables.

**Environment Variables:**
- MongoDB Configuration (DATABASE, USERNAME, DATABASE_PASSWORD)
- JSON Web Token Configuration (SECRET, JWT_EXPIRES_IN, JWT_COOKIE_EXPIRES_IN)

**API Reference:**
- Utilizing Postman for handling/testing all endpoints.
- Base URL endpoints: `http://127.0.0.1:3001/api/V1/` or `http://localhost:3001/api/v1/`

**Request Limit:**
- 100 requests per hour

**Query Operators:**
- Natours API employs various query operators like $gt, $gte, $lt, $lte for comparison operations.

**License**
[![License](https://img.shields.io/:License-MIT-blue.svg?style=flat-square)](http://badges.mit-license.org)
