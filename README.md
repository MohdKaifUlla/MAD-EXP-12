# Experiment 12 – Android HTTP Requests

## Student Details
- **Name:** Mohammed Kaif Ulla
- **USN:** 25MCAR0226

## Project Overview
This Android application demonstrates communication with RESTful web services using HTTP GET and POST requests. The application is developed using Kotlin in Android Studio and uses Retrofit and Gson for API communication and JSON data processing.

## Main Features
1. **GET User Details:** Retrieve user information by entering a user ID (1–10).
2. **POST Data:** Submit a post title and description to the server.
3. **Connection Status:** Displays API connection and request status.
4. **Request Counters:** Tracks GET and POST requests.
5. **Response Display:** Displays HTTP status and formatted JSON responses.
6. **Loading Indicator:** Shows progress during API operations.

## Technologies Used
- Android Studio
- Kotlin
- XML Layouts
- Retrofit 2
- Gson
- JSONPlaceholder REST API

## API Details
- **Base URL:** https://jsonplaceholder.typicode.com/
- **GET Endpoint:** users/{id}
- **POST Endpoint:** posts

JSONPlaceholder is used as a testing API. POST requests return simulated responses and do not permanently store submitted data.

## Project Structure
- **MainActivity.kt:** Handles application UI and user interactions.
- **ApiService.kt:** Defines API endpoints.
- **RetrofitClient.kt:** Configures Retrofit.
- **User.kt:** Contains user data model.
- **UserRepository.kt:** Manages API operations.
- **activity_main.xml:** Defines the application interface.

## How to Run
1. Extract the project ZIP file.
2. Open the Experiment12 folder in Android Studio.
3. Allow Gradle to sync dependencies.
4. Connect an Android device or start an emulator.
5. Run the application.
6. Enter a user ID between 1 and 10 and click Fetch User Details.
7. Enter a post title and description and click Send POST Request.
8. View the server response on the dashboard.

## Expected Output
- GET requests retrieve and display user information.
- POST requests submit data and display the server response.
- Request counters display the number of requests.
- Error messages appear when network requests fail.

## Student Details
**Name:** Mohammed Kaif Ulla

**USN:** 25MCAR0226
