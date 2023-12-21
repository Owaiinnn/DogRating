Dog Rating App

This HTML code represents a simple web application called the "Dog Rating App." The app allows users to view random dog images and rate them as either "Like" or "Dislike." Below is a read-me style overview of the code's structure and functionality.
Table of Contents

    Introduction
    Getting Started
    Application Features
    JavaScript Functionality
    Dependencies

Introduction

The Dog Rating App is a basic web application that allows users to interact with random dog images by rating them with "Like" or "Dislike" buttons. It also displays the counts of likes and dislikes for each image.
Getting Started
Dependencies

    Bootstrap CSS: Bootstrap CSS framework for styling.
    jQuery and Popper.js: JavaScript libraries used for Bootstrap functionality.
    Bootstrap JavaScript: JavaScript library for Bootstrap components.
    app.js: A custom JavaScript file for the application logic.

To get started, open this HTML file in a web browser. It doesn't require a server or build process to run. Make sure you have an internet connection to fetch random dog images.
Application Features
Dog Image Display

    A random dog image is displayed in a 300x300 pixel container.

Rating Buttons

    Users can rate the dog image using two buttons:
        "Like" (green button)
        "Dislike" (red button)

Like and Dislike Counts

    The app keeps track of the number of likes and dislikes.
    The counts are displayed below the rating buttons.

JavaScript Functionality

The JavaScript code in the <script> block is responsible for the app's functionality. It includes the following features:

    Event Listeners:
        The app waits for the DOM to be fully loaded before attaching event listeners.
        Event listeners are attached to the "Like" and "Dislike" buttons.

    Fetch Dog Image:
        A function, fetchDogImage(), is defined to retrieve random dog images from the "https://dog.ceo/api/breeds/image/random" API.
        The fetched image URL is set as the src attribute of the dogImage element.

    Local Storage:
        The app uses local storage to persist the counts of likes and dislikes across sessions.
        The counts are retrieved from local storage and displayed on the page.

    Button Click Actions:
        When a user clicks the "Like" button, the likes count is incremented, and the image is refreshed.
        When a user clicks the "Dislike" button, the dislikes count is incremented, and the image is refreshed.

    Initial Image Load:
        On page load, the fetchDogImage() function is called to load an initial random dog image.

Dependencies

    Bootstrap CSS: Styling for the application.
    jQuery and Popper.js: JavaScript libraries required for Bootstrap functionality.
    Bootstrap JavaScript: JavaScript library for Bootstrap components.
    app.js: A custom JavaScript file for the application logic.

This Dog Rating App provides a simple and fun way for users to interact with random dog images and rate them. Feel free to explore the code and customize it according to your needs.
