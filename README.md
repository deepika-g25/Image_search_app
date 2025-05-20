📷 Image Search App

A simple and responsive Image Search App built using HTML, CSS, and JavaScript. Users can search for images by keyword, and the app fetches and displays high-quality images from the Unsplash API.

✨ Features
Search for images by keyword
Fetches real-time data from Unsplash API
Responsive grid layout of images
Click images to view full size on Unsplash
Error handling for empty or failed searches

🧠 Concept

This app demonstrates how to:
Use fetch API to retrieve data from a third-party API
Dynamically update the DOM based on user input
Display images in a clean, responsive layout using CSS Grid or Flexbox
Handle asynchronous JavaScript operations and errors gracefully

🛠️ How It Works

The user enters a search term in the input box and clicks the search button.
JavaScript captures the input and sends a request to the Unsplash API with the search query.
The API returns JSON data containing image URLs and related metadata.
The app parses the JSON and creates image elements dynamically in the gallery section.
If no results or an error occurs, the app shows a user-friendly message.

📁 Project Structure

image-search-app/
├── index.html      # App structure and layout  
├── style.css       # Styling for the app  
└── script.js       # API calls and DOM manipulation logic

🚀 Getting Started

Get a free Unsplash API key from Unsplash Developers.
Clone this repository.
Open index.html in your browser.
Enter a search term and enjoy browsing images!

🧰 Technologies Used

HTML5
CSS3
JavaScript (ES6)
Unsplash API
