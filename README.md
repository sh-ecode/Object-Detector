# Visionary Tracker – Real-Time Object Detection & Tracking

## Team Name: SheCode
### Members:
- **Palak Sharma**  
- **Poorvi Gupta**  
- **Yashika Sharma**  

---

## 🌟 Overview  
Visionary Tracker is a **real-time object detection and tracking** system that leverages **AI-powered edge computing** to enhance security, retail, and assistive technology applications. The system operates entirely in the browser, offering **zero server dependency**, **real-time analytics**, and **audio alerts for critical objects** like weapons and obstacles.

## 🔥 Key Features  
### 1️⃣ Real-Time Object Detection  
- Utilizes **TensorFlow.js** and **COCO-SSD** for detecting objects live through a webcam.  
- Provides **bounding boxes** and **confidence scores** for each object.  

### 2️⃣ Smart Audio Alerts  
- **Dynamic alerts** based on object priority (e.g., immediate warning for weapons).  
- **Voice customization** using **Web Speech API**.  
- **Proximity awareness** to enhance safety.  

### 3️⃣ Performance Analytics Dashboard  
- **Real-time statistics** including detected objects, confidence levels, and FPS.  
- **Historical logs** for reviewing past detections.  
- **Interactive charts** using **Chart.js** to visualize trends.  

### 4️⃣ Snapshot Capture & Gallery  
- **One-click image saving** of detected objects.  
- **Encrypted snapshots** for security.  
- **Local storage** for viewing past detections.  

### 5️⃣ Responsive UI/UX  
- **Cross-platform compatibility** (desktop & mobile).  
- **Adaptive layout** for different screen sizes.  
- **Offline mode** for uninterrupted operation.  

### 6️⃣ Security & Privacy  
- **No data leaves the device** (runs entirely on the client side).  
- **Encrypted data storage** for user privacy.  
- Future integration with **IR cameras** for low-light performance.  

---

## 🚀 Technical Approach  
### Core Technologies:  
- **TensorFlow.js** – Browser-based machine learning for real-time object detection.  
- **COCO-SSD** – Pre-trained model for object detection.  
- **Web Speech API** – Provides audio feedback.  
- **Chart.js** – Enables data visualization in the analytics dashboard.  

### Workflow:  
1. **Camera Feed** → Object detection using **TensorFlow.js**  
2. **Bounding Boxes & Confidence Scores** displayed on UI  
3. **Critical Object Alerts** triggered via **Web Speech API**  
4. **Data Logged** for analytics and trend visualization  

---

## 🎯 Use Cases & Impact  
### 🔹 Smart Retail  
- Detects **customer dwell time** near products.  
- Helps **prevent shoplifting** by detecting concealed items.  

### 🔹 Home Security  
- Intruder alerts with **SMS/email notifications** (future update).  
- AI-powered **surveillance** with real-time analysis.  

### 🔹 Assistive Technology  
- **Audio navigation** for visually impaired individuals (e.g., "Chair 2 meters ahead").  
- AI-powered **environment detection** for enhanced mobility.  

**Case Study:**  
- **Pilot tested in a warehouse:** Reduced **theft by 30%** through real-time **knife detection**.  

---

## ⚠️ Limitations & Challenges  
### 🚧 Current Constraints  
1. **Browser Compatibility**  
   - Limited support for **Web Speech API** in **Safari**.  
2. **Lighting Conditions**  
   - **Low-light environments** reduce detection accuracy (~15% drop).  
3. **Occlusion Handling**  
   - **Partially hidden objects** (e.g., a gun in a pocket) may not be detected.  

### 🔧 Planned Mitigations  
- **IR Camera Support** (Future enhancement for better low-light detection).  
- **Custom Model Fine-Tuning** to improve occlusion handling.  

---


## 📌 How to Use  
### 1️⃣ Open the Application  
- Access the web app via **browser** (Google Chrome recommended).  

### 2️⃣ Enable Camera Permissions  
- Grant access to the webcam for live object detection.  

### 3️⃣ View Real-Time Analysis  
- The UI displays **bounding boxes**, **object names**, and **confidence scores**.  

### 4️⃣ Configure Alerts  
- Customize **audio notifications** based on object priority.  

### 5️⃣ Explore Analytics  
- Check **historical data** and **trends** using the dashboard.  

---

## 🤝 Acknowledgments  
- **TensorFlow.js & COCO-SSD** for **AI-powered object detection**.  
- **Web Speech API** for enabling **audio feedback**.  
- **Chart.js** for providing **interactive data visualization**.  
- **Open-source communities** for supporting machine learning innovations.  

---
