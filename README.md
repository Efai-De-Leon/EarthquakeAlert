# EarthquakeAlert

This simple React application fetches earthquake data from the USGS API [https://earthquake.usgs.gov/fdsnws/event/1/] and visualizes the most recent earthquake with a magnitude of 2.5 or greater.

## Features
**Real-time Data:** Fetches the latest earthquake data every minute.
**Color-coded Display:** Represents earthquake magnitude using different colors:
**Green:** Magnitude less than 4
**Yellow:** Magnitude between 4 and 6
**Orange:** Magnitude between 6 and 7
**Red:** Magnitude between 7 and 10
**Responsive Design:** Adapts to different screen sizes.

## Technologies Used
* React
* TypeScript
* Framer Motion (for animation)
* USGS API

## Installation and Running Locally
**Clone the repository:** git clone https://github.com/your-username/earthquake-visualizer.git
**Navigate to the project directory:** cd react-earthquake-colors-app
**Install dependencies:** npm install
**Start the development server:** npm run dev
