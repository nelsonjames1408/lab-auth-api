Lab 3 – API Authentication using JWT This project is a simple Authentication API built with Express.js + MySQL.
It demonstrates signup, login, logout (token revocation), and a protected profile endpoint** using JWT.
Passwords are securely stored using bcrypt hashing, and middleware validates tokens.

Steps to Setup and Install 

Clone the GitHub Repository:

text
git clone https://github.com/nelsonjames1408/lab-auth-api.git
Navigate into the Project Directory:

text
cd lab-auth-jwt-lab3
Install the Project Dependencies:

text
npm install
This command reads the package.json file and installs all required Node.js packages.

Run the Server in Development Mode:

text
npm run dev
This starts the development server with features like live reload and error reporting, as configured in the dev script within package.json.

These steps will get the server running in development mode so changes can be tested in real time during development.


Conclusion

During this project, I encountered challenges mainly with MySQL connection setup, JWT verification, and minor errors in Postman such as incorrect routes or missing headers. 
These experiences emphasized the importance of carefully reviewing error messages, maintaining consistency in environment variables, and methodically testing API endpoints step by step.
Overall, I learned the critical roles of bcrypt for securing passwords.
