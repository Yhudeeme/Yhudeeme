# Project Title
# Dalhousie University Admissions Assistant
## Table of Contents
Overview
- Project Overview
- Problem
- Solution
- Implementation details
- How to use
- Endpoints
- Contributors

## Overview
The Dalhousie University Admissions Assistant is a web application designed to simplify the admissions process for prospective students applying to Dalhousie University. This README provides an overview of the application's functionality, implementation details, and how to run the application locally.

## Problem
Applying to universities can be overwhelming and complex, especially for students unfamiliar with the process or specific requirements of the institution. The Dalhousie University admissions process involves various documents, deadlines, and criteria, which can be challenging to navigate, particularly for international students.

## Solution
The Dalhousie University Admissions Assistant aims to streamline the admissions process by providing a user-friendly platform that offers guidance, support, and resources tailored to each student's individual needs. The application leverages technology to provide personalized recommendations, track document submissions, send deadline reminders, and offer interview and exam preparation materials.

## Implementation Details
The backend of the application is implemented using Python and the Flask web framework. It provides endpoints for user registration, profile updates, and document uploads. The data is stored in a simple in-memory list, which can be replaced with a database in a production environment.

## How to use
1. Clone the repository to your local machine.
2. Install the required dependencies using pip: 'pip install Flask'
3. Navigate to the project directory in your terminal.
4. Run the Flask application by executing the following command 'python app.py'
5. The application will start running by default.
The app is configured to run with Flask. If you have Python and Flask, you can clone this repository and run it using `flask run`

## Endpoints
- **POST /register**: Register a new user with name, email, and academic background.
- **PUT /profile/update**: Update the user's profile information.
- **POST /documents/upload**: Upload a document for the user.

## Next Steps
- Enhance the backend with additional features such as deadline reminders and interview/exam preparation resources.
- Develop the frontend of the application using HTML, CSS, and JavaScript.
- Implement user authentication and authorization for secure access to user data.
- Deploy the application to a cloud platform for production use.

## Contributors
- [Mercy Chikezie](https://github.com/yhudeeme/-assisten)
- 
<!---
Yhudeeme/Yhudeeme is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
