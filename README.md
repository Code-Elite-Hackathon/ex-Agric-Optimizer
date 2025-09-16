# ex-Agric-Optimizer

Project Documentation – ex-Agri Optimizer
Team: ex-Code
Team Members:
1. Ernest Edem Dzisah
2. John Machot
3. Josheph Habah
Overview
ex-Agri Optimizer is an AI-powered farm dashboard built with HTML, CSS, and JavaScript.
It helps farmers and researchers monitor soil moisture, weather conditions, and crop health in real time, while providing AI-like farming recommendations for better decision-making.
________________________________________
Features
•	 Soil Moisture Monitoring – Simulated real-time soil data visualization with charts.
•	 Weather Forecast – Displays live (or simulated) temperature data with trend charts.
•	Crop Health Tracking – Indicates overall plant health (Healthy, Moderate, Unhealthy).
•	AI Recommendations – Provides actionable crop-specific suggestions (irrigation, fertilizer, pest alerts, etc.).
•	Interactive Dashboard – Built with Chart.js for real-time data visualization.
•	Responsive Design – Works across desktop and mobile devices.
________________________________________
 Tech Stack
•	Frontend: HTML5, CSS3, JavaScript (Vanilla)
•	Charts: Chart.js
•	Styling: Custom CSS (responsive, grid layout)
•	Backend (optional): FastAPI (Python) – for real sensor data & API integration
________________________________________
 Installation & Setup
1.	Clone or download the project:
2.	git clone https://github.com/your-username/ex-agri-optimizer.git
3.	cd ex-agri-optimizer
4.	Run the project locally:
o	Option 1: Open index.html directly in your browser.
o	Option 2 (recommended for API usage): Run a local server:
o	python -m http.server 8080
Then open http://127.0.0.1:8080 in your browser.
5.	(Optional) Connect to backend APIs:
o	Weather API: Replace the placeholder API key with a valid OpenWeather key.
o	Sensor API: Point fetch() calls to your FastAPI backend for real telemetry.
________________________________________
Data Update Frequency
•	Default update: every 3 minutes
•	Can be configured in index.html:
•	setInterval(updateDashboard, 180000); // 3 minutes
________________________________________
Project Structure
ex-agri-optimizer/
│── index.html        # Main dashboard page
│── style.css         # Styling (inline or separate)
│── script.js         # Dashboard logic & chart updates
│── logo.png          # Project logo
│── bg.jpg            # Background image
│── README.md         # Documentation
________________________________________
 Future Improvements
•	Replace simulated data with real IoT sensor input (via FastAPI).
•	Store data in a database (PostgreSQL / MongoDB) for historical analysis.
•	Integrate machine learning models for predictive insights (yield, pests).
•	Add user authentication for farm-specific dashboards.

_______________________________________________________
Readme
_______________________________________________________

# ex-Agri Optimizer
**AI-Powered Dashboard for Real-Time Farm Analysis**

## Overview
ex-Agri Optimizer is a web dashboard for farmers that tracks soil, weather, and crop health while giving AI-like actionable recommendations.

## Features
- Soil Moisture Monitoring with Chart.js
- Weather Forecast (real or simulated)
- Crop Health Tracking
- AI-based Recommendations
- Responsive Design

## Tech Stack
- HTML, CSS, JavaScript
- Chart.js
- (Optional) FastAPI backend for real data

## Setup
```bash
git clone https://github.com/your-username/ex-agri-optimizer.git
cd ex-agri-optimizer
python -m http.server 8080
```
Then open: `http://127.0.0.1:8080`

## Data Update
Dashboard refreshes every **3 minutes**:
```js
setInterval(updateDashboard, 180000);
```

## Future Plans
- Integrate IoT sensors
- Database storage & analytics
- ML-based predictive farming insights
