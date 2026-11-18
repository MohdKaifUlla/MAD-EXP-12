# Experiment 12 – Android HTTP Requests

## Student Details
- **Name:** Mohammed Kaif Ulla
- **USN:** 25MCAR0226

## Project Overview
This Android application demonstrates how to communicate with a RESTful web service using HTTP **GET** and **POST** requests. The app is built with Kotlin and Android Studio and uses Retrofit with Gson to make network requests and parse JSON responses.

## Main Features
1. **GET User Details:** Enter a user ID (1–10) and retrieve user information from the API.
2. **POST Data:** Enter a post title and description and submit the data to the API.
3. **Connection Status:** Displays the current request/connection state.
4. **Request Counters:** Shows the number of GET and POST requests performed during the current app session.
5. **Response Display:** Shows the HTTP status and formatted JSON response or an error message.
6. **Loading Indicator:** Displays progress while a request is being processed.

## Technologies Used
- Android Studio
- Kotlin
- XML layouts
- Retrofit 2
- Gson
- JSONPlaceholder REST API

## API Details
- **Base URL:** `https://jsonplaceholder.typicode.com/`
- **GET endpoint:** `users/{id}`
- **POST endpoint:** `posts`

The application uses the public JSONPlaceholder testing API. POST requests demonstrate submission and return a simulated response; they do not permanently create a real post on a production server.

## Project Structure
```text
Experiment12/
├── app/
│   ├── src/main/
│   │   ├── java/com/example/experiment12/
│   │   │   ├── api/          # Retrofit API interface and client
│   │   │   ├── models/       # Data models
│   │   │   ├── repository/   # API repository
│   │   │   └── MainActivity.kt
│   │   ├── res/layout/       # Activity UI
│   │   └── AndroidManifest.xml
│   └── build.gradle.kts
├── gradle/
└── settings.gradle.kts
```

## How to Run
1. Extract the project ZIP file.
2. Open the `Experiment12` folder in Android Studio.
3. Allow Gradle to sync and download the required dependencies.
4. Run the application on an Android emulator or a physical Android device.
5. Ensure the device has an active internet connection.
6. Enter a user ID from 1 to 10 and tap **Fetch User Details** to test GET.
7. Enter a post title and description, then tap **Send POST Request** to test POST.

## Expected Output
- A successful GET request displays the selected user's name, email, phone number, address, HTTP status, and JSON response.
- A successful POST request displays the response returned by JSONPlaceholder.
- If the network is unavailable or a request fails, the app displays an appropriate error/status message.

## Student
**Mohammed Kaif Ulla**  
**USN: 25MCAR0226**
