# Travel Advisor – Google Maps Based React Application

Travel Advisor is a location-based web application built using React.js that helps users discover nearby restaurants, hotels, and tourist attractions. The application integrates Google Maps with external travel data APIs to provide real-time, interactive, and location-aware recommendations.

---

![Travel Advisor](https://i.ibb.co/qph2cZn/image.pngg)

## Overview

The application automatically detects the user’s geographical location and displays an interactive map along with a list of nearby places. Users can search for locations manually, explore places directly on the map, and filter results based on ratings. Data is fetched dynamically from third-party APIs and rendered efficiently using React’s component-based architecture.

This project demonstrates practical usage of API integration, map-based UI development, and modern frontend best practices.

---

## Features

- Real-time geolocation detection
- Interactive Google Maps with custom markers
- Nearby restaurants, hotels, and attractions listing
- Manual location search
- Rating-based filtering
- Responsive and clean user interface
- Dynamic data fetching from external APIs

---

## Tech Stack

- **Frontend:** React.js
- **UI Framework:** Material-UI
- **Maps:** Google Maps JavaScript API
- **APIs:** RapidAPI (Travel Advisor API, OpenWeatherMap)
- **HTTP Client:** Axios
- **Build Tool:** Create React App

---

## Application Workflow

1. User opens the application
2. Browser geolocation API retrieves latitude and longitude
3. Google Maps loads centered on the detected location
4. Travel data is fetched from RapidAPI based on coordinates
5. Results are displayed on the map and in a list view
6. User can search, filter, and interact with map markers

---

## Project Structure

src/
├── components/
│ ├── Header
│ ├── List
│ ├── Map
│ └── PlaceDetails
├── api/
│ └── index.js
├── App.js
└── index.js
