# Rockfall Prediction Command Center

A modern AI-powered disaster response system with real-time monitoring, risk prediction, and resource management capabilities.

## Features

- **Real-time Risk Monitoring**: Interactive map with color-coded risk zones
- **AI-Powered Alerts**: NLP-processed emergency communications
- **Resource Management**: Dynamic allocation tracking and optimization
- **Predictive Analytics**: ML-based recommendations for preventive actions
- **Dark Theme Dashboard**: Modern, responsive interface

## Tech Stack

### Backend (FastAPI)
- FastAPI for REST API
- Python virtual environment
- CORS enabled for frontend integration

### Frontend (React)
- React 18 with modern hooks
- Tailwind CSS for styling
- Leaflet.js for interactive maps
- Lucide React for icons
- Responsive design

## Setup Instructions

### 1. Backend Setup

```powershell
# Navigate to project directory
cd C:\Users\LAKSHYA\Desktop\ROCKFALL

# Activate virtual environment
.\myenv\Scripts\Activate.ps1

# Install Python dependencies
pip install -r requirements.txt

# Start FastAPI server
uvicorn main:app --reload
```

The API will be available at: http://127.0.0.1:8000

### 2. Frontend Setup

```powershell
# Navigate to frontend directory
cd frontend

# Install Node.js dependencies
npm install

# Start React development server
npm start
```

The React app will be available at: http://localhost:3000

## API Endpoints

- `GET /` - API status
- `GET /api/active-risks` - Current rockfall risks
- `GET /api/emergency-messages` - NLP-processed alerts
- `GET /api/resource-allocation` - Resource status
- `GET /api/recommended-actions` - AI recommendations
- `GET /api/system-status` - System component status

## Project Structure

```
ROCKFALL/
├── main.py                 # FastAPI backend
├── requirements.txt        # Python dependencies
├── myenv/                 # Python virtual environment
├── frontend/              # React application
│   ├── src/
│   │   ├── components/    # React components
│   │   ├── App.js         # Main app component
│   │   └── index.js       # Entry point
│   ├── public/            # Static files
│   └── package.json       # Node.js dependencies
└── README.md              # This file
```

## Usage

1. Start the FastAPI backend server
2. Start the React frontend development server
3. Open http://localhost:3000 in your browser
4. View real-time disaster monitoring dashboard

## Dashboard Components

- **Top Navbar**: System status indicators and navigation tabs
- **Left Sidebar**: Active disaster zones and emergency messages
- **Center Map**: Interactive risk visualization with Leaflet.js
- **Right Sidebar**: Resource allocation and AI recommendations

The dashboard automatically updates with real-time data and provides a comprehensive view of the disaster response situation.
