# 👤 Apollo Patient Kiosk: Face Recognition + Wait Time Dashboard

A real-time face recognition system for hospital patient check-in/check-out, with live dashboard showing waiting times.

---

## 🎯 Purpose

- Automate patient identification using face scan → fetch UHID, Name, Mobile  
- Track check-in/check-out times → calculate wait duration  
- Display live dashboard of patients waiting >2 mins  
- Auto-remove patient from dashboard when they leave camera view  
- Built for Apollo Hospitals (simulated environment)
- [Click Here 👇]  
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c7c2059c-d390-4609-900a-48ed82006784" />



---

## 🖼️ Screenshots

### 1. Face Scan + Patient Info Display

[![Face Scan]https://github.com/Kumarrajasekharreddy/Face-Recognition-Checkin-Checkout-Dashboard/blob/main/System%20recognizes%20patient%20.png
*System recognizes patient → displays UHID, Name, Mobile*

### 2. Multi-Person Detection + Wait Time Tracking

[![Multi-Face Detection]https://github.com/Kumarrajasekharreddy/Face-Recognition-Checkin-Checkout-Dashboard/blob/main/Detects%20multiple%20patients.png
*Detects multiple patients → assigns ID, tracks time since check-in*

### 3. Patient Leaves → Auto-Removed from Dashboard

[![Patient Left]https://github.com/Kumarrajasekharreddy/Face-Recognition-Checkin-Checkout-Dashboard/blob/main/When%20patient%20moves%20out%20of%20frame.png
*When patient moves out of frame → removed from dashboard*

### 4. Live Waiting Patients Dashboard

[![Waiting Dashboard]https://github.com/Kumarrajasekharreddy/Face-Recognition-Checkin-Checkout-Dashboard/blob/main/Shows%20patients%20waiting%20.png
*Shows patients waiting >2 mins → helps staff prioritize*

---

## 🛠️ Tech Stack

- Python
- OpenCV (for face detection)
- Flask (for web interface)
- SQLite / PostgreSQL (for storing patient data)
- HTML/CSS (for dashboard styling)

---

## 💡 Key Feature Highlights

> ✅ **Real-Time Face Recognition**: Scans faces → matches with database → displays patient details instantly  
> ✅ **Wait Time Tracker**: Starts timer when patient enters frame → stops when they leave  
> ✅ **Auto-Remove Logic**: If patient is not seen for 10 seconds → removed from dashboard  
> ✅ **Live Dashboard**: Shows only patients waiting >2 minutes → auto-refreshes every 5 seconds  
> ✅ **Stable Display**: Even if face is briefly missed → details stay visible for 3 seconds

