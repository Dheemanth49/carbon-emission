# EcoEnergy Dashboard 🌱

A comprehensive full-stack ML application for sustainable energy consumption monitoring with gamification features.

## 🚀 Features

### 📊 Data Analytics & ML
- **Real-time Energy Monitoring**: Track consumption patterns with 3-minute granularity
- **Carbon Footprint Calculation**: Automatic CO₂ emission tracking (0.82 kg CO₂/kWh)
- **ML Forecasting**: Prophet/LSTM models for consumption prediction
- **Anomaly Detection**: Identify unusual consumption patterns
- **Professional EDA**: Comprehensive exploratory data analysis with visualizations

### 🎮 Gamification System
- **Badge System**: 
  - 🌱 Eco Saver (< 2 kWh/day)
  - 🌍 Green User (2-5 kWh/day)
  - 🔥 Carbon Heavy (5-8 kWh/day)
  - 🏆 Efficient Hero (> 8 kWh but improving)
- **Leaderboard**: Weekly rankings based on efficiency
- **Progress Tracking**: Visual progress bars and achievement history

### 💡 Smart Recommendations
- **Personalized Suggestions**: AI-powered energy-saving tips
- **Potential Savings Calculator**: CO₂ and cost reduction estimates
- **Peak Hour Optimization**: Time-based usage recommendations

### 🔐 User Management
- **Secure Authentication**: Flask-Login with bcrypt password hashing
- **Multi-user Support**: Individual dashboards per meter/user
- **Session Management**: Secure login/logout functionality

### 📱 Modern Frontend
- **Responsive Design**: Bootstrap 5 with mobile-first approach
- **Interactive Charts**: Plotly.js visualizations
- **Professional UI**: Clean, modern interface with intuitive navigation


## 🚀 Quick Start

### 1. Prerequisites
- Python 3.8+
- pip (Python package manager)

### 2. Installation

```bash
# Clone or download the project
cd carbon-emission

# Install dependencies
pip install -r requirements.txt

```

### 3. Dataset Setup
Ensure your dataset (`total_dataset.csv`) is in the `data/` directory with columns:
- `x_Timestamp`: DateTime (every 3 minutes)
- `t_kWh`: Energy consumed in kWh
- `z_Avg Voltage (V)`: Average voltage
- `z_Avg Current (A)`: Average current
- `y_Freq (Hz)`: Frequency
- `meter`: Meter ID


**Made with ❤️ for a sustainable future** 🌍

