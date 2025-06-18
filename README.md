# European Weather Forecast (EurOrbit)

A modern, responsive web app that allows users to view a 7-day weather forecast for major European cities. Powered by the free 7Timer! API, this project is designed to help travelers plan their trips with confidence.

## Features
- Select from a list of major European cities
- View a 7-day weather forecast with icons, temperature, and weather descriptions
- Responsive design using Bootstrap for mobile and desktop
- Attractive, accessible UI with custom color palette
- Graceful error handling for API/network issues

## Demo
![Screenshot](images/banner.jpg) <!-- Replace with your own screenshot if available -->

## Getting Started

### Prerequisites
- A modern web browser
- (Recommended) A local web server (e.g., VS Code Live Server, Python's `http.server`, or `npx serve`)

### Setup
1. **Clone or download this repository.**
2. **Open the project folder in your code editor.**
3. **Start a local server:**
   - **VS Code:** Right-click `index.html` and select "Open with Live Server"
   - **Python:**
     ```bash
     python -m http.server
     ```
   - **Node.js:**
     ```bash
     npx serve
     ```
4. **Open `index.html` in your browser via the local server URL.**

> **Note:** The 7Timer! API does not support CORS for file:// URLs. You must use a local server to fetch weather data.

## Usage
1. Select a city from the dropdown menu.
2. The app will display a 7-day weather forecast for the selected city, including icons and temperature.
3. If the API is unavailable or there is a network error, a user-friendly error message will be shown.

## Technologies Used
- **HTML5 & CSS3**
- **Bootstrap 4/5** (for responsive design)
- **JavaScript (ES6+)**
- **[7Timer! API](http://www.7timer.info/doc.php?lang=en)** (for weather data)
- **Weather icons** (custom and/or from [Flaticon](https://www.flaticon.com/))

## Credits
- **Weather Data:** [7Timer! API](http://www.7timer.info/doc.php?lang=en)
- **Icons:** Custom icons and/or [Flaticon](https://www.flaticon.com/)
- **Images:** [Pixabay](https://pixabay.com/) (for royalty-free images)
- **UI Framework:** [Bootstrap](https://getbootstrap.com/)

## License
This project is for educational and non-commercial use only. See [7Timer! API Terms](http://www.7timer.info/doc.php?lang=en) for data usage restrictions.

---

**Created by [Md Shahria Alam]** 
