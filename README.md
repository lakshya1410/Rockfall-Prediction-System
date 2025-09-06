# AI-Powered Rockfall Prediction System 🚀

An advanced geological risk assessment and management system that combines FastAPI backend with a modern React frontend to provide real-time rockfall prediction and monitoring capabilities.

![System Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![React](https://img.shields.io/badge/React-18.0+-61dafb)
![FastAPI](https://img.shields.io/badge/FastAPI-Latest-009688)

## 🌟 Features

### 🎯 **Core Functionality**
- **Real-time Geological Risk Assessment** with AI-powered prediction models
- **Interactive Risk Zone Mapping** using Leaflet.js with satellite imagery
- **Dynamic Dashboard** with live monitoring and status indicators
- **Emergency Alert System** with automated notifications
- **Resource Management** for emergency response coordination

### 🗺️ **Map Features**
- **Indian Geological Focus**: Centered on coordinates 24.27°N 80.17°E
- **Color-coded Risk Zones**: Critical, High, Medium, and Safe zone visualization
- **Incident Markers**: Real-time geological event tracking
- **Satellite Overlay**: High-resolution terrain analysis
- **Interactive Popups**: Detailed risk information and incident data

### 🎨 **UI/UX Excellence**
- **Professional Dark Theme** with gradient styling
- **Enhanced Navbar** with single-line title and compact design
- **Responsive Layout** with sidebar navigation
- **Real-time Status Indicators** for AI models and system health
- **Modern Typography** with optimized spacing and readability

## 🎯 Technology Stack

### Backend
- **FastAPI**: Modern, fast web framework for Python APIs
- **Uvicorn**: ASGI server for running FastAPI applications
- **Python 3.8+**: Core programming language
- **CORS Middleware**: Cross-origin resource sharing support

### Frontend
- **React 18**: Modern JavaScript framework for UI
- **Tailwind CSS**: Utility-first CSS framework
- **Leaflet.js**: Interactive mapping library
- **Lucide React**: Beautiful icon library
- **Webpack**: Module bundler and development server

### Development Tools
- **Git**: Version control system
- **npm**: Package manager for Node.js
- **pip**: Package manager for Python
- **Virtual Environment**: Isolated Python environment

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- Node.js 16 or higher
- npm or yarn package manager

### Backend Setup (FastAPI)

1. **Clone the repository**
   ```bash
   git clone https://github.com/lakshya1410/Rockfall-Prediction-System.git
   cd Rockfall-Prediction-System
   ```

2. **Create and activate virtual environment**
   ```bash
   # Windows
   python -m venv myenv
   myenv\Scripts\activate

   # Linux/Mac
   python3 -m venv myenv
   source myenv/bin/activate
   ```

3. **Install Python dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Start the FastAPI server**
   ```bash
   uvicorn main:app --reload --host 127.0.0.1 --port 8000
   ```

   The backend will be available at: `http://localhost:8000`
   API documentation: `http://localhost:8000/docs`

### Frontend Setup (React)

1. **Navigate to frontend directory**
   ```bash
   cd frontend
   ```

2. **Install Node.js dependencies**
   ```bash
   npm install
   ```

3. **Start the React development server**
   ```bash
   npm start
   ```

   The frontend will be available at: `http://localhost:3000`

## 🛠️ API Endpoints

### Geological Risk Management
- `GET /` - Health check endpoint
- `GET /geological-risks` - Retrieve active geological risks
- `POST /geological-risks` - Add new geological risk assessment
- `GET /emergency-messages` - Get emergency notifications
- `POST /emergency-messages` - Create emergency alert
- `GET /resource-allocation` - Get resource distribution data
- `POST /resource-allocation` - Allocate emergency resources
- `GET /emergency-actions` - Retrieve recommended actions
- `POST /emergency-actions` - Log emergency response actions

## 📊 System Features

### Navigation Tabs
- **Command Center**: Main operational dashboard
- **Data Ingestion**: Geological data input and processing
- **Model Predicting**: AI prediction model status and results
- **Rockfall Forecast**: Predictive analysis and forecasting

### Status Monitoring
- **DEM Model**: Digital Elevation Model processing status
- **CNN Model**: Convolutional Neural Network analysis status
- **Weather API**: Meteorological data integration status
- **Seismic Monitor**: Earthquake and seismic activity tracking

### Risk Zone Classifications
- 🔴 **Critical Risk**: Immediate evacuation required
- 🟠 **High Risk**: Enhanced monitoring and preparation
- 🟡 **Medium Risk**: Regular assessment and monitoring
- 🟢 **Safe Zone**: Stable geological conditions

## 📁 Project Structure

```
Rockfall-Prediction-System/
├── 📄 main.py                 # FastAPI backend application
├── 📄 requirements.txt        # Python dependencies
├── 📄 .gitignore             # Git ignore rules
├── 📄 README.md              # Project documentation
├── 📁 myenv/                 # Python virtual environment (not in repo)
└── 📁 frontend/              # React frontend application
    ├── 📁 public/            # Static assets
    ├── 📁 src/               # React source code
    │   ├── 📁 components/    # React components
    │   │   ├── 📄 Navbar.js           # Enhanced navigation bar
    │   │   ├── 📄 MapSection.js       # Interactive geological map
    │   │   ├── 📄 LeftSidebar.js      # Risk monitoring panel
    │   │   ├── 📄 RightSidebar.js     # Resource management panel
    │   │   └── 📄 RockfallDashboard.js # Main dashboard layout
    │   ├── 📄 App.js         # Main React application
    │   ├── 📄 App.css        # Enhanced styling
    │   └── 📄 index.js       # React entry point
    ├── 📄 package.json       # Node.js dependencies
    └── 📄 tailwind.config.js # Tailwind CSS configuration
```

## 🚧 Development Status

- ✅ **Backend API**: Fully functional FastAPI server
- ✅ **Frontend Dashboard**: Complete React application with enhanced UI
- ✅ **Map Integration**: Interactive Leaflet map with Indian coordinates
- ✅ **Real-time Monitoring**: Live status indicators and risk assessment
- 🔄 **AI Models**: In development for advanced prediction capabilities
- 📋 **Database Integration**: Planned for persistent data storage

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🆘 Support

For support and questions:
- Create an issue on GitHub
- Email: lakshya1410@example.com
- Documentation: Available in this README

---

**Built with ❤️ for geological safety and disaster prevention**

🌍 **Repository**: https://github.com/lakshya1410/Rockfall-Prediction-System.git
