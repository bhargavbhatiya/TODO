# MERN Stack Todo Application with authetication 

This is a simple todo application built using the MERN (MongoDB, Express, React, Node.js) stack. It allows users to create, update, delete, and filter tasks.


## Project Setup

### Front-End (React)

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the client directory: `cd frontend`
3. Install dependencies: `npm install`
4. Start the development server: `npm start`
5. Access the application at: `http://localhost:3000`

### Back-End (Node.js with Express)
The backend of the application is built using Node.js, Express.js, and MongoDB. Here are the steps to set up the backend:

1. Navigate to the backend directory: `cd backend`
2. Install dependencies: `npm install`
3. Set up environment variables:
   - Create a `.env` file in the root directory of the `backend` folder.
3. Start the backend server: `npm start`

5. The server will run on port 5000 by default.


## Technologies Used

- MongoDB: NoSQL database for storing task data.
- Express: Node.js web application framework for building the API.
- React: Front-end library for building user interfaces.
- Node.js: JavaScript runtime for building server-side applications.
- Axios: HTTP client for making requests from the React front-end to the Express back-end.
- Mongoose: MongoDB object modeling tool for Node.js.
- JWT for authentication


## Testing

To run tests, use the following commands:

- Backend tests: `cd backend && npm test`
- Frontend tests: `cd frontend && npm test`
- Unit tests for both front-end and back-end components.
- Test coverage for critical parts of the application such as API endpoints, data validation, and user interactions.

## Security

- User authentication and authorization using JWT.
- Server-side validation to prevent common vulnerabilities.
- Protection against SQL injection and cross-site scripting (XSS).
- Secure storage of sensitive information such as database credentials.





## Planning

### Frontend planning

![pic1](./Frontend_Plan.png)


### Backend planning

![pic2](./Backend_Plan.png)

### Screenshots

![ss1](./screenshots/login.png)
![ss2](./screenshots/register.png)
![ss3](./screenshots/dashboard.png)




