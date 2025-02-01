# Advanced Air Traffic Management and Monitoring System

## Overview
This project focuses on developing an integrated system for monitoring, analyzing, and managing air traffic for airports and Advanced Air Mobility (AAM)/Urban Air Mobility (UAM). The project is divided into three key modules, each designed to enhance operational efficiency, safety, and data-driven decision-making.

---

## Modules

### **Module 1: 3D Map as the Central Interface**
The 3D Map serves as the main user interface for real-time monitoring and control. Features include:
- **Real-Time Visualization**: Aircraft and vehicle tracking with category-specific filtering.
- **Rule Definitions**: Setting restricted zones, speed limits, and temporal traffic rules.
- **Interactive Layers**: Weather conditions, parking zones, and no-fly areas.
- **Alerts**: Notifications for rule violations and safety hazards.
- **Planning Tools**: Traffic predictions and route optimization.

Technologies:
- **Front-End**: Mapbox GL JS, Deck.gl
- **Back-End**: Flask/FastAPI, PostgreSQL with PostGIS
- **Integrations**: OpenSky Network, Flightradar24

---

### **Module 2: Camera Integration with Computer Vision**
Enhances situational awareness using live camera feeds and automated analysis:
- **Real-Time Monitoring**: Object detection and anomaly tracking.
- **Safety Analysis**: Alerts for unauthorized zone entries or operational risks.
- **Data Storage**: Video logging for audits and investigations.
- **Map Integration**: Sync camera feeds with map indicators.

Technologies:
- **Machine Learning**: DeepSeek, TensorFlow, PyTorch
- **Integration**: APIs for camera systems
- **Storage**: Indexed video and event data

---

### **Module 3: Reporting and Analytics**
Provides analytical tools and insights for performance and safety optimization:
- **Customizable Reports**: Detailed traffic, rule violations, and resource utilization.
- **Dashboards**: Key metrics and predictive analytics.
- **Visualizations**: Interactive graphs and trend analysis.
- **Alerts**: Automated report-based notifications.

Technologies:
- **Data Analysis**: Pandas, NumPy
- **Visualization**: Matplotlib, Plotly
- **Integration**: PostgreSQL, export formats (CSV, PDF)

---

## Development Workflow
1. **Version Control**: Project repository maintained on GitHub.
2. **Testing**: Iterative testing for front-end and back-end modules to ensure modular independence.
3. **Tools**: 
   - Front-end and back-end development on Cursor AI Assistant.
   - Continuous integration and containerization using Docker.

---

## Getting Started
### Prerequisites
- Python 3.x
- PostgreSQL with PostGIS
- Node.js for front-end dependencies