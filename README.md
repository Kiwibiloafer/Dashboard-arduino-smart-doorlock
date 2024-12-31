## Repository Contents

1. **index.html**
   - The main HTML file for the web dashboard. It displays the current status of the door and includes buttons to lock and unlock the door.

2. **config.js**
   - A JavaScript file containing the Firebase configuration and login details.

## Setup Instructions

1. **Set Up Firebase Project**
   - Configure the application in the Firebase project settings.

2. **Update Configuration**
   - Populate the `config.js` file with the configuration details provided by Firebase (e.g., API key, database URL, and authentication details).

3. **Run the Dashboard**
   - Open the `index.html` file in a web browser. The dashboard will display the current door status and include buttons to control the door.

## Features

- **Real-time Data Display**
  - The dashboard shows the latest door status by reading data from the Firebase Realtime Database.

- **Remote Door Control**
  - Includes buttons to lock and unlock the door, with changes reflected in the database.

- **Easy Configuration**
  - Simple setup by editing the `config.js` file with Firebase details.

## Notes

- Ensure your Firebase Realtime Database rules allow appropriate read and write access.
- Use a secure network to host and access the web dashboard.
- Test the configuration by ensuring data updates correctly in the database.