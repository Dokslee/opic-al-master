# Weather Dashboard

## Features
- Provides real-time weather data for various locations.
- Displays weather forecasts and historical data.
- User-friendly interface for seamless navigation.
- Integration with multiple weather APIs.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Dokslee/opic-al-master.git
   ```
2. Navigate to the project directory:
   ```bash
   cd opic-al-master
   ```
3. Install necessary dependencies:
   ```bash
   npm install
   ```
4. Start the application:
   ```bash
   npm start
   ```

## API Usage
- The application fetches weather data from the following APIs:
  - OpenWeatherMap
  - WeatherAPI

- Example API call:
   ```bash
   GET /weather?location={location}
   ```

## Project Structure
```
opic-al-master/
├── src/
│   ├── components/    # React components
│   ├── services/      # API services
│   ├── utils/         # Utility functions
│   └── App.js         # Main application file
├── public/
│   ├── index.html     # HTML template
│   └── favicon.ico    # Favicon
├── package.json        # Project metadata and dependencies
└── README.md          # Project documentation
```
