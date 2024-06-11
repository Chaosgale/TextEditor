# Web-Based Text Editor Application

This web-based text editor offers a variety of features designed to enhance your text editing experience. Below is a comprehensive guide to its functionality and usage.

## Project Structure

The application follows a client-server architecture. Upon opening the project, you will find separate directories for the client and server components.

## Starting the Application

To launch the application, navigate to the root directory in your terminal and execute `npm run start`. This command will start the backend server and serve the client-side application.

## JavaScript Bundling

The application's JavaScript files are bundled using webpack. This process occurs automatically when you run the application from the terminal.

## Webpack Plugins Utilization

Several webpack plugins are employed to enhance the application:
- An HTML file is generated for the application.
- A service worker is created to manage offline capabilities.
- A manifest file is generated for Progressive Web App (PWA) support.

## Modern JavaScript Support

The text editor leverages modern JavaScript features, ensuring compatibility and smooth performance in contemporary web browsers.

## IndexedDB Integration for Data Persistence

Upon launching the text editor, an IndexedDB database is immediately created. The application automatically saves any content entered, and retrieves it upon reopening, ensuring no data is lost.

## Installation as a Desktop Application

You can install the web application to your desktop by clicking the Install button. This will add an icon to your desktop, allowing for easy access and use as a standalone application.

## Service Worker and Offline Capabilities

A service worker is registered using Workbox when the application loads. This service worker pre-caches static assets, ensuring the application can function offline and load faster on subsequent visits.

## Deployment 

https://webtexteditor-5t8d.onrender.com/
