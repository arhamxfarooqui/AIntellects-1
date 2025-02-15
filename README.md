# 🚦 AIntellects 🚀  

AIntellects is a smart, AI-powered traffic management system designed to improve urban mobility by leveraging machine learning and real-time data. It integrates multiple components to detect incidents, analyze traffic density, and provide a user-friendly interface for monitoring traffic conditions.  

## ✨ Features  

- 🛑 *Incident Detection Model:* Identifies traffic incidents in real time.  
- 🚗 *Traffic Optimization Model:* Analyzes traffic densities to improve management strategies.  
- ⚡ *FastAPI Backend:* Facilitates seamless communication between ML models, the database, and the frontend.  
- 📊 *React Frontend Visualization:* Displays traffic data using graphs and pie charts.  
- 📢 *Incident Reporting:* Allows incident reports to be generated and forwarded.  

## 🔄 Workflow  

1. *📥 Data Collection:*  
   - Real-time traffic data is collected and sent to the backend.  
2. *🧠 Incident Detection & Traffic Analysis:*  
   - The incident detection model analyzes the incoming data to identify accidents or disruptions.  
   - The traffic optimization model studies traffic densities to determine congestion levels and suggest better management strategies.  
3. *💾 Database Storage & API Handling:*  
   - The processed data is stored in an SQLite3 database.  
   - FastAPI provides endpoints to fetch incident reports and traffic data.  
4. *📡 Frontend Visualization & Reporting:*  
   - The React frontend fetches and displays traffic densities using graphs and pie charts.  
   - Users can view real-time traffic conditions and submit incident reports.  
   - Incident reports can be forwarded for action.  

## 🛠 Tech Stack  

- *🤖 Machine Learning:* Models for incident detection and traffic analysis.  
- *🖥 Backend:* FastAPI, SQLite3 (for data storage).  
- *🎨 Frontend:* React (deployed on Vercel), providing visual insights into traffic conditions.  
- *🚀 Deployment:* Render (FastAPI backend) and Vercel (React frontend).  

## 📦 Frontend Dependencies  

The React frontend utilizes the following dependencies:  

### *📌 Core Dependencies*  
sh
npm install react react-dom react-router-dom

### *🎨 Material-UI Dependencies*  
sh
npm install @mui/material @mui/icons-material @emotion/react @emotion/styled
npm install @mui/x-charts
npm install styled-components

### *✨ Animations & Effects*  
sh
npm install aos
npm install typewriter-effect

### *🎠 Carousel/Slider*  
sh
npm install react-slick slick-carousel

### *🛠 Development Dependencies*  
sh
npm install -D @vitejs/plugin-react
npm install -D vite
npm install -D @eslint/js eslint eslint-plugin-react eslint-plugin-react-hooks eslint-plugin-react-refresh globals


## ⚙ Installation & Setup  

1. 📝 Clone the repository:  
   sh  
   git clone https://github.com/mohdTahaRafi/AIntellects.git  
   cd AIntellects  
     
2. 📌 Install backend dependencies:  
   sh  
   pip install -r requirements.txt  
     
3. 🚀 Run the FastAPI server:  
   sh  
   uvicorn main:app --reload  
     
4. 📂 Navigate to the React frontend directory and install dependencies:  
   sh  
   cd frontend  
   npm install  
     
5. ▶ Start the React frontend:  
   sh  
   npm run dev  
     

## 📡 API Endpoints  

- POST /incidents - 📤 models sends a report.  
- GET /traffic-density - 📊 Retrieve real-time traffic density data.  
- POST /optimize-traffic - 🔄 Optimize traffic based on density analysis.  

## 🚀 Deployment  

- *🖥 Backend:* Hosted on Render.  
- *🌐 Frontend:* React app hosted on Vercel.
