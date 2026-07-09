# 🌤 Weather App

A beautiful, responsive web application built with **Django** that provides real-time weather information for any city in the world using the **OpenWeatherMap API**. 

The app features a modern **Glassmorphism UI** with smooth hover effects, dynamic weather icons, and comprehensive environmental metrics.

---

## 🚀 Features

* **Real-time Weather Data**: Search and get instant weather details for any city.
* **Modern Glassmorphic UI**: Transparent cards, soft blur effects, and sleek layout.
* **Key Metrics Displayed**:
  * Temperature (Current, Min, Max in °C)
  * Weather Description & Icon
  * Humidity 💧
  * Wind Speed 🌬 & Direction 🧭
  * Cloud Cover ☁
  * Visibility 👁
  * Atmospheric Pressure 🌡
* **Error Handling**: Displays clean warnings when a city is not found or if the network is down.

---

## 🛠 Tech Stack

* **Backend**: Django (Python web framework)
* **Frontend**: HTML5, Vanilla CSS3 (Glassmorphism layout)
* **API**: OpenWeatherMap API
* **Libraries**: `requests` (for making HTTP API calls)

---

## 📁 Project Structure

```text
weatherapp/
├── weather/                  # Django App folder
│   ├── static/css/style.css  # Modern CSS styles (Glassmorphism design)
│   ├── templates/
│   │   ├── base.html         # Base HTML layout
│   │   ├── home.html         # Weather dashboard content
│   │   └── partials/
│   │       └── navbar.html   # Search bar & navigation
│   ├── views.py              # Main logic calling OpenWeatherMap API
│   ├── urls.py               # App routing
│   └── models.py
├── weatherapp/               # Django config folder
│   ├── settings.py           # Project settings
│   └── urls.py               # Main project routing
├── manage.py                 # Django management script
└── .gitignore                # Files to ignore in Git
```

---

## ⚙️ Installation & Setup

Follow these simple steps to run this project locally on your machine:

### Prerequisite
Make sure you have **Python** installed on your system. You can download it from [python.org](https://www.python.org/).

### Step 1: Clone the Repository
```bash
git clone https://github.com/NavyaAvilala2714/Weather-App.git
cd Weather-App
```

### Step 2: Create a Virtual Environment
It is highly recommended to use a virtual environment to manage dependencies.
* **Windows**:
  ```bash
  python -m venv .venv
  .venv\Scripts\activate
  ```
* **macOS / Linux**:
  ```bash
  python3 -m venv .venv
  source .venv/bin/activate
  ```

### Step 3: Install Dependencies
Install Django and requests library:
```bash
pip install django requests
```

### Step 4: Run the Development Server
Run the migrations and start the server:
```bash
python manage.py migrate
python manage.py runserver
```

### Step 5: View the Application
Open your browser and navigate to:
```text
http://127.0.0.1:8000/
```

---

## 🛡 License
This project is open-source and available under the [MIT License](LICENSE).