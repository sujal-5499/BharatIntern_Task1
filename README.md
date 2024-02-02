# Registration Form Project
This repository contains a simple registration form project developed using HTML, CSS, Node.js, and MongoDB.
The project consists of the main registration form (`index.html`), a success page for successful registrations (`signup_successful.html`), the styling for the pages (`style.css`), and the server-side logic (`index.js`) to handle form submissions and store user information in MongoDB.

## Project Structure
- **index.html**: The main registration form that users fill out to sign up. It includes fields for Name, Age, Email, Phone Number, Gender, and Password.
- **signup_successful.html**: The success page displayed after a user successfully registers. It includes a message and a background image.
- **style.css**: Stylesheet for formatting and styling the HTML pages. It uses the 'Poppins' font and includes styles for the registration form and success page.
- **index.js**: Node.js script to handle server-side logic. It uses Express for handling HTTP requests, Body Parser for parsing request bodies, and Mongoose to interact with MongoDB. The script establishes a connection to the database and handles POST requests to the "/sign_up" endpoint, storing user information in the 'users' collection.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/registration-form-project.git
   cd registration-form-project
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Run the application:
   ```bash
   node index.js
   ```
   The application will be accessible at [http://localhost:3000](http://localhost:3000).

## Dependencies
- Express: `npm install express`
- Body Parser: `npm install body-parser`
- Mongoose: `npm install mongoose`

## Database Configuration
The project is configured to use MongoDB. Update the MongoDB connection string in the `mongosse.connect` method in `index.js` with your own MongoDB connection string.

```javascript
mongosse.connect('your-mongodb-connection-string')
```

## Usage
1. Fill out the registration form at [http://localhost:3000](http://localhost:3000).
2. Upon successful registration, you will be redirected to the success page.

# Project Screenshots
1. Image1
![image](https://github.com/PrinceRaj-CU/BharatIntern_Task1/assets/83507753/9b30cbae-1d68-43de-a932-e0596c432177)
2. Image2
![image](https://github.com/PrinceRaj-CU/BharatIntern_Task1/assets/83507753/1770c263-e4b2-4119-8764-3cef2a763bd2)
3. Image3
![image](https://github.com/PrinceRaj-CU/BharatIntern_Task1/assets/83507753/32d56fcb-1a49-4e23-86a3-4576b349f62d)

Feel free to fork, modify, and use the code for your own projects! If you encounter any issues or have suggestions for improvements, please create an issue or pull request.
