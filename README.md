
Built by https://www.blackbox.ai

---

# Location Tracker

## Project Overview

Location Tracker is a web application designed to visualize and track a user's geographical location in real-time. The app features an interactive map that displays the user’s current location along with location accuracy and history. Built using modern web technologies, it provides an intuitive user interface powered by Leaflet for mapping and Tailwind CSS for styling.

## Installation

To run the Location Tracker application on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd location-tracker
   ```

2. **Open the HTML file in a browser**:
   Just open `index.html` in your preferred web browser. No additional libraries need to be installed as they're all included via CDN.

## Usage

1. Upon loading the application, you will see a map displayed, showing your current location (if permissions are granted).
2. The application automatically retrieves your geographic coordinates and displays them in the "Current Location" section.
3. You can refresh your location by clicking the "Refresh" button in the header.
4. The location history will be displayed in the "Location History" section, allowing you to track previous locations.

## Features

- Interactive map using Leaflet.js.
- Displays current geographical coordinates (latitude, longitude, accuracy).
- Keeps a history of location changes (though initial state indicates no history).
- Responsive design powered by Tailwind CSS.
- Refresh location button to manually update coordinates.

## Dependencies

The project uses the following external libraries:
- **Leaflet.js**: For map creation and handling.
- **Font Awesome**: For iconography.
- **Tailwind CSS**: For styling.

These dependencies are loaded via CDN in the `index.html` file:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.7.1/dist/leaflet.css" />
<script src="https://unpkg.com/leaflet@1.7.1/dist/leaflet.js"></script>
<script src="https://cdn.tailwindcss.com"></script>
```

## Project Structure

```
location-tracker/
│
├── index.html             # Main HTML file for the application
└── script.js              # JavaScript file for handling location logic
```

- **index.html**: This is the main entry point for the application. It contains the user interface, including the map and location display sections.
- **script.js**: Contains the JavaScript code that implements the location tracking functionality and updates the UI with the latest data.

---

Feel free to explore the code and customize it according to your needs. Happy tracking!