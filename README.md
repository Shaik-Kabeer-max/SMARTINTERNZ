# 🚦 Traffic Volume Estimation Web App

This Streamlit-based web application predicts the **traffic volume** on the **Metro Interstate Highway** using historical weather, time, and holiday data. It uses a **Random Forest Regressor** model trained on the **Metro Interstate Traffic Volume dataset**.

---

## 🔍 Features

* Predict traffic volume based on:

  * Holiday status
  * Temperature, Rain, and Snow
  * Weather condition
  * Date and time (year, month, day, hour, minute, second)
* Visualize **simulated traffic volume** for all 24 hours of a day
* Identify **peak hour** with maximum traffic

---

## 📊 Dataset

* **Name:** Metro Interstate Traffic Volume
* **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume)
* **Size:** \~40,000 rows of hourly data from 2012–2018
* **Features Used:**

  * `holiday`, `temp`, `rain_1h`, `snow_1h`, `weather_main`, `date_time`

---

## 🧠 ML Model

* **Algorithm:** Random Forest Regressor
* **Scaler:** StandardScaler
* **Train/Test Split:** 80/20
* **Performance:** Trained locally for demonstration purposes (not optimized for production)

---

## 🚀 How to Run

1. **Clone the repository**:

   ```bash
   git clone https://github.com/<your-username>/traffic-volume-estimation.git
   cd traffic-volume-estimation
   ```

2. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

3. **Place the dataset**:

   * Download `Metro_Interstate_Traffic_Volume.csv` and place it in the project folder.

4. **Run the Streamlit app**:

   ```bash
   streamlit run app.py
   ```

---

## 🖥️ UI Preview

| Prediction Panel                | Hourly Simulation                  |
| ------------------------------- | ---------------------------------- |
| ![UI](images/ui_prediction.png) | ![Chart](images/ui_simulation.png) |

---

## 📂 Project Structure

```
traffic-volume-estimation/
│
├── app.py                     # Streamlit App Code
├── Metro_Interstate_Traffic_Volume.csv
├── requirements.txt           # Python dependencies
└── README.md
```

---

## 📦 Requirements

```txt
streamlit
pandas
numpy
scikit-learn
matplotlib
```

Install using:

```bash
pip install -r requirements.txt
```

---

## 📜 License

This project is for educational and academic purposes only.
