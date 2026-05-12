# 🧾 Shift Pay Calculator

A mobile-friendly web application for calculating and tracking shift-based earnings using real payroll data.

## 🚀 Overview

This project was built to simplify how casual workers estimate their pay without needing to manually reference spreadsheets.

Users upload an Excel payroll timetable once per device. The application processes the file and stores the extracted data locally, meaning the document does not need to be re-uploaded on future visits.

The app automatically:
- Detects pay periods
- Tracks paydays
- Calculates earnings based on shifts worked
- Progresses to the next pay period after payday

## ✨ Features

- 📊 Excel file upload and parsing (XLSX)
- 💾 Local data storage (no re-upload required)
- 📅 Automatic pay period detection and updates
- 💰 Shift-based earnings calculation
- 🌙 Dark mode support
- ⚙️ Customisable pay settings
- 📱 Mobile-first, app-style interface

## 🧠 How It Works

1. Upload your payroll timetable (Excel file)
2. The app extracts pay periods, cut-off dates, and paydays
3. Data is saved locally on your device
4. Enter number of shifts worked
5. The app calculates your estimated pay

Once a payday has passed, the app automatically removes the completed period and moves to the next one.

## 🛠 Tech Stack

- HTML  
- CSS  
- JavaScript  
- XLSX.js  
- LocalStorage  

## 🌐 Deployment

- Version control and hosting via GitHub  
- Live deployment via Netlify  

## 📸 Live Demo

👉 https://calculator-shift.netlify.app

## 📦 Source Code

👉 this repo is the code needed for the web app 

## 👤 Author

Connor Moizer  
https://connormoizer.com
