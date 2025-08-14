🚦 Traffic Volume Estimation Web App

Yeh web application Metro Interstate Highway par traffic volume predict karta hai, historical weather, time, aur holiday data ka use karke.
Isme Random Forest Regressor model use hua hai jo Metro Interstate Traffic Volume dataset par train kiya gaya hai.


---

🔍 Features

Predict traffic volume based on:

Holiday status

Temperature, Rain, and Snow

Weather condition

Date and time (year, month, day, hour, minute, second)

Visualize simulated traffic volume for all 24 hours of a day

Identify peak hour with maximum traffic



---

📊 Dataset

Name: Metro Interstate Traffic Volume

Source: UCI Machine Learning Repository

Size: ~40,000 rows of hourly data from 2012–2018

Features Used: holiday, temp, rain_1h, snow_1h, weather_main, date_time



---

🧠 ML Model

Algorithm: Random Forest Regressor

Scaler: StandardScaler

Train/Test Split: 80/20

Performance: Trained locally for demonstration purposes (not optimized for production)



---

🖥 UI Preview

app.py → Main backend Python code

index.html → Frontend home page

output.html → Prediction results page



---

📂 Project Structure

traffic-volume-estimation/
│
├── app.py                     # Backend code
├── index.html                  # Home page UI
├── output.html                 # Prediction output page
├── Metro_Interstate_Traffic_Volume.csv
├── requirements.txt            # Python dependencies
└── README.md


---

📜 License

This project is for educational and academic purposes only.