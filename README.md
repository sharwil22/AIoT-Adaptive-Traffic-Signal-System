# AIoT-Adaptive-Traffic-Signal-System

## 🎥 Demo Video
👉 [Watch Demo](https://drive.google.com/file/d/1FMBXMYgWmxljm3ESb5XbIuJrRhrQ5dTw/view?usp=share_link)



## 📌 Overview
This project focuses on optimizing traffic signal timing using computer vision. Traditional traffic systems use fixed timers, which often lead to congestion and inefficiency.

This system uses YOLOv5 for real-time vehicle detection and adjusts signal timing dynamically based on traffic density.

---

## 🚨 Problem
- Fixed traffic signals do not adapt to real-time conditions  
- Leads to congestion and unnecessary waiting  
- Can cause unsafe behavior like signal jumping  

---

## 💡 Solution
- Detect vehicles using YOLOv5  
- Estimate traffic density from video frames  
- Adjust signal timing dynamically using rule-based logic  

---

## ⚙️ How It Works

1. Input video from traffic camera  
2. YOLOv5 detects vehicles (cars, bikes, buses)  
3. Count vehicles in frame / region  
4. Calculate traffic density  
5. Apply rule-based logic:
   - Higher density → longer green signal  
   - Lower density → shorter signal  

---



## 📸 Output

![Detection](output.jpg) https://drive.google.com/file/d/12161vvpzjgeTrA3WOmB-oysU_USw2CWS/view?usp=share_link


---

## 🛠️ Tech Stack
- Python  
- YOLOv5  
- OpenCV  
- Google Colab  

---

## 📊 Results
- Improved traffic flow efficiency compared to fixed-timer systems  
- Demonstrates practical application of computer vision in smart city systems  

---

## 📄 Research Connection
This project is supported by a research study comparing YOLOv5, YOLOv8, Faster R-CNN, and SSD for vehicle detection in Indian traffic scenarios.

---

## 🚀 Future Scope
- Real-time CCTV integration  
- AI-based adaptive signal optimization  
- Smart city deployment  

---

## 👨‍💻 Author
Sharwil Bhende
