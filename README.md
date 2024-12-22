# Razorpay Payment-Link Generator

This project is a React-based web application that allows users to submit their details (name, email, and contact) and interact with an API to generate Razorpay payment links. It demonstrates the integration of APIs with React, form handling, and error management.

Features:
--------
User-friendly form to collect name, email, and contact details.
Handles form submission using axios to send POST requests to a Razorpay API endpoint.
Displays API responses directly in the UI, whether success or error.
Implements a loading state with a dynamic submit button (Submitting... while loading).
Comprehensive error handling for network and server-side issues.

Tech Stack:
-----------
Frontend: React.js (with Hooks)
HTTP Client: Axios

How to Run:
-----------
1.Clone the repository:
git clone https://github.com/Rahamatunnisa1121/L4G-Interface
cd L4g_Interface

2.Install dependencies:
npm install

3.Start the development server:
npm start

4.Fill out the form and test the functionality.

API Endpoint:
The application interacts with the following API endpoint: https://qhf89t91pj.execute-api.ap-south-1.amazonaws.com/V1/razorpay-payment-link-creation

Project Structure:
src/App.js: Contains the main component with form handling and API integration logic.
src/index.js: Entry point for the React application.

Future Improvements:
Add validation for form fields (e.g., required fields, valid email format).
Enhance UI/UX with better styling and feedback indicators.
Implement success/error modals for better user experience.
Extend functionality to customize Razorpay payment link parameters.
Make this Responsive






