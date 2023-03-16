# ShoppingAppTesting
Complete android Unit, Integration, Integrated and UI testing using TDD approach

This repository contains an Android project with sample code for implementing TDD (Test-Driven Development) in Android app development. The project includes testing for Room database, Retrofit network setup, ViewModel testing using both fake and default repository, and testing using Hilt dependency injection framework.

<h2>Prerequisites</h2>
- Android Studio (version 4.0 or later) <br>
- Gradle (version 6.5 or later)
<h2>Getting Started</h2>
To get started with the project, follow these steps:

1. Clone the repository to your local machine:
<pre>
    <code>
        git clone https://github.com/<username>/<repository-name>.git
    </code>
</pre>

2. Open the project in Android Studio.
3. Build and run the project to ensure that it is set up correctly.

<h2>Testing</h2>
The project includes the following types of tests:

<h3>Room Database Testing</h3>
The RoomDatabaseTest class contains unit tests for testing the Room database implementation. These tests ensure that the database is properly set up and that data is stored and retrieved correctly.

<h3>Retrofit Network Setup Testing</h3>
The RetrofitNetworkTest class contains unit tests for testing the Retrofit network setup. These tests ensure that the API is properly set up and that data is retrieved correctly from the server.

<h3>ViewModel Testing using Fake and Default Repository</h3>
The ViewModelTest class contains unit tests for testing the ViewModel implementation. These tests ensure that the ViewModel properly handles data and that data is displayed correctly in the UI.

The FakeRepository class is used for testing the ViewModel without actually connecting to the API. The DefaultRepository class is used for testing the ViewModel with a real API connection.

<h3>Testing using Hilt</h3>
The project includes tests for Hilt dependency injection using the HiltTest class. These tests ensure that dependencies are properly injected and that the app functions correctly.

<h2>Conclusion</h2>
This Android TDD testing project provides a sample implementation of TDD in Android app development, including testing for Room database, Retrofit network setup, ViewModel testing using both fake and default repository, and testing using Hilt dependency injection framework. You can use this project as a starting point for your own Android TDD testing projects.




