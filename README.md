# Smart Garden Scheduler

## 🌱 Project Overview
The **Smart Garden Scheduler** is a web-based application designed to help users efficiently manage and automate their garden watering schedules.  
It provides a **clean and user-friendly UI** for interaction and uses **weather forecasting** to optimize watering times, conserving water and improving plant health.  

The project integrates:
- **Frontend:** HTML, CSS, JavaScript for a responsive and intuitive interface.
- **Backend:** Java Spring Boot for handling business logic and scheduling tasks.
- **Weather Forecasting:** External API integration to fetch real-time and forecast weather data.

By analyzing upcoming weather conditions, the scheduler can skip watering on rainy days or adjust schedules during hot, dry periods.



## 🚀 How to Run Locally

### 1. **Clone the Repository**
git clone <repository-url>
cd smart-garden-scheduler

2. Setup Backend (Spring Boot)
1)Open the project in your preferred IDE (IntelliJ, Eclipse, VS Code with Java extensions).

2)Make sure you have:
1)Java 17+ installed
2)Maven installed

3) Configure your API key in application.properties:
  properties:
  weather.api.key=YOUR_API_KEY
4)Build and run:
mvn spring-boot:run

3. Setup Frontend
1) The index.html, style.css, and JavaScript files are located in the src/main/resources/static folder.
2) Access the application in your browser:
http://localhost:8080
