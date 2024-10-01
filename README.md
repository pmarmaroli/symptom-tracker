# Symptom Tracker

A simple web-based application for tracking and logging symptoms over time. This app allows users to add symptoms, log them with timestamps, visualize their occurrence using a chart, and download logs in CSV format.

## Features

- **Add Symptoms**: Input and save symptoms for tracking.
- **Log Symptoms**: Record the date and time of each occurrence.
- **Visualize Symptoms**: Generate a line chart that displays the occurrences of a selected symptom over time.
- **Delete Symptoms**: Remove a symptom and its associated logs.
- **Download Logs**: Export symptom logs as a CSV file.

## Tech Stack

- **HTML/CSS/JavaScript**: For the basic structure, styling, and interactivity of the app.
- **Chart.js**: To generate dynamic charts for visualizing symptom data.
- **Moment.js**: To format and manage time in logs and charts.
- **LocalStorage**: Used to store symptoms and logs locally on the user's device.

## How to Use

1. **Clone the repository**:

   ```bash
   git clone https://github.com/pmarmaroli/symptom-tracker.git
   ```

2. **Open the `index.html` file in a browser**:
   Navigate to the project folder and double-click the `index.html` file or open it using a web browser to start using the app.

3. **Access the app online**:

   If you prefer to access the app directly without cloning the repository, you can visit the hosted version at:
   https://pmarmaroli.github.io/symptom-tracker/

## Usage Instructions

- **Add a symptom**: Enter a symptom name in the input box and click the 'Add Symptom' button.
- **Log a symptom occurrence**: Click the 'Log Date & Time' button next to the symptom to record the current timestamp.
- **View logs**: Logged entries appear under the 'Log History' section.
- **Visualize symptoms**: Select a symptom from the dropdown to generate a line chart showing the number of times it has been logged over the days.
- **Download logs**: Click the 'Download CSV' button to export all logged symptoms and timestamps as a CSV file.
