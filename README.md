
Built by https://www.blackbox.ai

---

```markdown
# Link Generator - Location Tracker

## Project Overview
The **Link Generator - Location Tracker** is a web application that allows users to generate unique tracking links. When accessed, these links will retrieve the user's current geographical location using the browser's geolocation API and display it on a map. This project integrates HTML, CSS, and JavaScript to create an interactive front-end experience.

## Installation
To get started with the Link Generator - Location Tracker, follow these steps:

1. **Clone the repository** to your local machine using:
    ```bash
    git clone https://github.com/your-username/link-generator-location-tracker.git
    ```
2. **Navigate to the project directory**:
    ```bash
    cd link-generator-location-tracker
    ```
3. **Open the `index.html`** file in your web browser to run the application.

You do not require any additional server setup as this application can be run directly from static files.

## Usage
1. Visit the application by opening `index.html` in your web browser.
2. Click on the "Generate Link" button to create a unique tracking link.
3. Copy the generated link and share it.
4. When opened, the link will request access to the user's geolocation data.
5. After granting permission, the user's latitude and longitude will be displayed along with an embedded Google Map pinpointing their location.

## Features
- Generate unique tracking links.
- Retrieve and display user location through the browser’s Geolocation API.
- Embedded Google Map for visual representation of the location.
- User-friendly interface with responsive design.

## Dependencies
This project uses the following external libraries:
- **Tailwind CSS**: For styling the user interface.
- **Font Awesome**: For icons used in buttons.

You can reference these libraries in your HTML files as shown in the code.

## Project Structure
The project consists of the following files:
```
/link-generator-location-tracker
│
├── index.html       # Main page for generating tracking links.
└── trace.html       # Page for displaying the user's location based on the generated link.
```

### HTML Files
- `index.html`: Provides the interface for generating tracking links.
- `trace.html`: Displays the user's geolocation information and shows the location on a map.

### JavaScript Functions
- `generateUniqueId()`: Generates a unique identifier for the tracking link.
- `getQueryParam(param)`: Retrieves query parameters from the URL.
- `initMap(lat, lng)`: Initializes and displays the Google Map based on the user's coordinates.

---

For any issues or contributions, please feel free to create an issue or submit a pull request on this repository.
```