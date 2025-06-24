Flutter Login Task – RoundTechSquare Internship


This project is a basic login screen built using Flutter as part of the RoundTechSquare internship assessment through Cuvette.

✅ Features Implemented
🖥️ UI Components
Login screen with two input fields: Email and Password
Login button with loading state
Basic Material Design UI

✅ Validation
Displays error if fields are empty
Shows API error if credentials are invalid

🔌 API Integration
Uses HTTP POST request to this dummy API: https://api.escuelajs.co/api/v1/auth/login
Sends email and password in JSON body

🔐 On Successful Login
Shows "Login Successful" message using Get.snackbar
Navigates to a Home Screen
Stores the authentication token securely using flutter_secure_storage


❌ On Failure
Displays server error message from the API

📦 Tech Stack Used
Flutter

GetX – for state management and navigation

http – for REST API calls

flutter_secure_storage – for securely storing the token

🧪 Test Credentials
The following test credentials work with the dummy API:

Email: john@mail.com

Password: changeme
