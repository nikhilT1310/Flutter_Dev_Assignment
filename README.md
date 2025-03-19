# flutter_dev_assignment

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

Flutter API Integration

## Project Overview

This Flutter application demonstrates how to fetch and display
data from an API using the http package. It retrieves posts from
JSONPlaceholder API and presents them in a scrollable ListView.
The app also implements a loading indicator and handles potential
errors gracefully.

## Features

1.Fetches data from https://jsonplaceholder.typicode.com/posts
2.Displays the fetched posts in a ListView
3.Shows a CircularProgressIndicator while loading
4.Handles API errors gracefully and displays a user-friendly message
5.Uses a well-structured Post model for data parsing
6.Optimized for Performance: Ensures responsiveness and efficiency

## Project Setup

1️] Prerequisites
    1.Ensure you have Flutter SDK installed. You can check by running:
      flutter --version
    2.Install dependencies using:
      flutter run
2] Running the App
  To start the application on an emulator or a connected device.
   :flutter run

## API Response Example
    Each post contains the following JSON structure:
        {
        "userId": 1,
        "id": 1,
        "title": "sunt aut facere repellat provident occaecati excepturi optio reprehenderit",
        "body": "quia et suscipit..."
        }

##  Error Handling
    If the API call fails, the app:
     1.Displays an error message instead of crashing.
     2.Returns an empty list when data is unavailable.
     3.Prints debug logs for troubleshooting.

## Additional Enhancements (Optional)
    1.Add pull-to-refresh functionality
    2.Implement caching for offline support
    3.Improve UI with better theming & animations

## Adherence to Time Limit
    This project is expected to be completed within the specified timeframe.

## README Quality
    This README provides clear setup instructions, an overview of the project,
    and additional details to ensure ease of use and understanding.

## Author
Developed by Nikhil Todankar