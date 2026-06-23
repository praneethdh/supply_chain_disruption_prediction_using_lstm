# Supply Chain Disruption Prediction System: AI-Powered Predictive Logistics Intelligence

## About The Project


The Supply Chain Disruption Prediction System is a full-stack AI application that predicts potential disruptions in logistics and supply chain operations across India. The system combines Isolation Forest, LSTM, and XGBoost models to analyze shipment data, weather conditions, and historical patterns to estimate disruption risks.

The backend is built using FastAPI for efficient model inference and API services, while the frontend uses React 19, Three.js, and Tailwind CSS to provide an interactive 3D visualization of the supply chain network. The application also integrates real-time weather data and explainable AI insights, helping users identify risk factors and make informed logistics decisions.
.

## 🔗 Live Space Deployment

**Live Web Application:**
https://huggingface.co/spaces/praneeth-dh/supply-chain-disruption-prediction

## Library Requirements

### Backend

* FastAPI
* Uvicorn
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* TensorFlow / Keras
* Requests

### Frontend

* React 19
* Three.js
* React Three Fiber
* GSAP
* Tailwind CSS
* TypeScript
* Axios

## Getting Started

Follow these instructions to set up and run the project locally.

## Installation Steps

### Option 1: Installation from GitHub

#### 1. Clone the Repository

```bash
git clone https://github.com/your-username/supply-chain-disruption-prediction.git
```

#### 2. Create a Virtual Environment

```bash
python -m venv venv
```

#### 3. Activate the Virtual Environment

**Windows**

```powershell
.\venv\Scripts\activate
```

**Linux/macOS**

```bash
source venv/bin/activate
```

#### 4. Install Backend Dependencies

```bash
pip install -r requirements.txt
```

#### 5. Start FastAPI Backend

```bash
python server.py
```

Backend will run on:

```text
http://localhost:8000
```

#### 6. Setup Frontend

```bash
cd frontend
npm install
```

#### 7. Start Frontend

```bash
npm run dev
```

Frontend will run on:

```text
http://localhost:5173
```

### Option 2: Run with Docker

#### Build Docker Image

```bash
docker build -t supply-chain-predictor .
```

#### Run Docker Container

```bash
docker run -p 7860:7860 supply-chain-predictor
```

## 💻 How to Use

### Step 1

Launch both the FastAPI backend and React frontend.

### Step 2

Open the application in your browser.

### Step 3

Explore the interactive 3D supply chain visualization representing major logistics hubs across India.

### Step 4

Select shipment and route information.

### Step 5

Allow the system to fetch real-time weather intelligence and process shipment data.

### Step 6

Generate disruption risk predictions using the AI ensemble pipeline.

### Step 7

Review risk scores, confidence metrics, and explainable AI insights for decision-making.

## Key Features

* AI-powered disruption prediction system
* Isolation Forest anomaly detection
* LSTM-based temporal forecasting
* XGBoost risk classification
* Real-time weather intelligence integration
* Explainable AI insights
* Interactive 3D logistics visualization
* React 19 and Three.js frontend
* FastAPI backend services
* Docker deployment support
* Modern responsive UI using Tailwind CSS

## Project Structure

```text
├── frontend/
│   ├── src/components/
│   ├── src/services/
│   ├── src/types/
│   └── assets/
│
├── datasets/
│
├── models/
│   ├── isolation_forest.pkl
│   ├── xgboost_model.pkl
│   └── lstm_model.h5
│
├── server.py
├── requirements.txt
├── Dockerfile
└── README.md
```

## Contributing

Contributions are welcome and greatly appreciated.

### Report Bugs

Open an issue describing the bug and reproduction steps.

### Contribute Code

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature/AmazingFeature
```

3. Commit your changes

```bash
git commit -m "Add Amazing Feature"
```

4. Push your branch

```bash
git push origin feature/AmazingFeature
```

5. Open a Pull Request

### Suggestions

Feature requests and improvement ideas are always welcome.

If you find this project useful, please consider giving it a ⭐ on GitHub.

## License

This project is licensed under the MIT License.


## Acknowledgements

Special thanks to the developers and communities behind:

* React
* FastAPI
* Three.js
* React Three Fiber
* GSAP
* Tailwind CSS
* TensorFlow
* XGBoost
* Scikit-learn
* Open-Meteo API
* Docker
* Hugging Face Spaces
