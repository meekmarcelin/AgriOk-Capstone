Project Overview

AgriOk is an IoT-driven precision agriculture platform designed to empower farmers with actionable insights using real-time data from sensors in the field. It provides a combination of data analytics and machine learning to help optimize crop health, irrigation, fertilization, and pest control. Through an easy-to-use web interface, farmers can access recommendations on managing their farms, receive alerts, and monitor data from various sensors (e.g., soil moisture, temperature, humidity).

The platform incorporates a robust backend, scalable cloud infrastructure, and seamless integration of IoT devices for data collection and management. The aim is to promote sustainable agriculture through technology, allowing farmers to increase productivity while reducing resource waste.

                             Features
1. Real-Time Data Collection:
IoT sensors monitor soil moisture, temperature, humidity, and pH levels.
Data is sent to a local server, processed using the MQTT protocol, and stored in a time-series database for real-time analytics.

2. Machine Learning-Driven Insights:
Predictive models forecast irrigation needs, detect anomalies (e.g., pest outbreaks), and generate recommendations for optimal farm management.

3. User Interface:
Responsive web interface built with React.js allows farmers to access their data, receive alerts, and view real-time recommendations.
Data visualization of trends using D3.js/Chart.js for easy monitoring of farm conditions.

4. Cloud-Based Infrastructure:
Hosted on cloud platforms for scalability and automated deployment.
Integrates IoT data via MQTT for real-time data streaming.

5. Database Management:
Scalable time-series database (InfluxDB) stores IoT data, while PostgreSQL manages users and recommendations.

6. Mobile Accessibility:
Responsive design ensures easy access from smartphones and tablets for farmers on the go.


         Technologies Used
Frontend:
React.js for UI development.
D3.js/Chart.js for real-time data visualization.
HTML5, CSS3, JavaScript for core interface design.

Backend:
Python (Flask/Django) or Node.js for API management and data serving.
Machine learning models built with TensorFlow, Keras, and Scikit-learn for predictive analysis.

Database:
InfluxDB for IoT sensor data (time-series).
PostgreSQL for user and recommendation management.

IoT Integration:
MQTT broker (Mosquitto) for handling IoT sensor data streams.
Local server for data pre-processing before transmission to the cloud.

Cloud Infrastructure:
AWS IoT Core or Google Cloud IoT for hosting and managing IoT devices.
Docker and Kubernetes for containerization and automated deployment pipelines.

Repository link: https://github.com/meekmarcelin/AgriOk-Capstone.git

          Deployment Plan

Cloud Deployment:
The web app and backend will be hosted on AWS/GCP.
Use Docker for containerization and Kubernetes for scaling microservices.

CI/CD Pipelines:
Automated deployment using Jenkins/GitHub Actions, ensuring continuous delivery of updates.

Monitoring:
Grafana will be integrated for real-time monitoring of server and IoT data performance.
Design Files
             Mockups

<img width="464" alt="agriok artchitecture" src="https://github.com/user-attachments/assets/02d4e116-5079-4552-aa01-56e001d67a9c">


link to mockup: https://agriokrwanda.renderforestsites.com/




