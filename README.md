## 👤 Apollo Patient Kiosk: Face Recognition + Wait Time Dashboard

[Click Here 👇](./face-scan.png)  
![Face Scan](./face-scan.png)

- Built a real-time face recognition system for hospital patient check-in/check-out → fetches UHID, Name, Mobile instantly
- Implemented wait time tracking → auto-removes patient from dashboard when they leave camera view
- Used Python, OpenCV, Flask, and HTML/CSS to build a live dashboard showing patients waiting >2 mins
- Enhanced problem-solving, automation, and real-world system design skills
- Simulated for Apollo Hospitals — ready for enterprise deployment

---

## 🖼️ Screenshots (Click to View Full Size)

### 1. Face Scan + Patient Info Display

[![Face Scan](./face-scan.png)](./face-scan.png)  
*System recognizes patient → displays UHID, Name, Mobile*

### 2. Multi-Person Detection + Wait Time Tracking

[![Multi-Face Detection](./multi-face.png)](./multi-face.png)  
*Detects multiple patients → assigns ID, tracks time since check-in*

### 3. Patient Leaves → Auto-Removed from Dashboard

[![Patient Left](./patient-left.png)](./patient-left.png)  
*When patient moves out of frame → removed from dashboard*

### 4. Live Waiting Patients Dashboard

[![Waiting Dashboard](./waiting-dashboard.png)](./waiting-dashboard.png)  
*Shows patients waiting >2 mins → helps staff prioritize*

---

## 🎥 Watch the Demo

▶️ [Watch Full Demo on YouTube](https://youtu.be/your-video-id-here)

*(Click to see real-time face detection, check-in tracking, auto-remove, and live dashboard updates)*

---

## 🛠️ Tech Stack

- Python
- OpenCV (for face detection)
- Flask (for web interface)
- SQLite / PostgreSQL (for storing patient data)
- HTML/CSS (for dashboard styling)

---

## 📦 How to Run (If Someone Wants to Clone)

```bash
git clone https://github.com/Kumarrajasekharreddy/Face-Recognition-Checkin-Checkout-Dashboard.git
cd Face-Recognition-Checkin-Checkout-Dashboard
pip install -r requirements.txt
python app.py
