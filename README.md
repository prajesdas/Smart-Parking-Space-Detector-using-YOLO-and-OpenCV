# 🚗 Smart Parking Space Detector using YOLO and OpenCV 🅿️  

## 🔍 Overview  
This project utilizes **YOLO (You Only Look Once) and OpenCV** to detect and monitor parking spaces in real-time. It helps optimize parking lot management by identifying vacant and occupied spots with high accuracy.  

## 🛠️ Features  
✅ **Real-time Parking Detection** using YOLOv4/YOLOv8  
✅ **OpenCV for Image Processing**  
✅ **Bounding Boxes & Object Detection** for parked cars  
✅ **Customizable Parking Zone Mapping**  
✅ **Supports Live Camera Feeds & Video Input**  

## 📸 Demo 

![Screenshot 2025-02-19 211822](https://github.com/user-attachments/assets/9e088105-cc5e-419a-844c-24575bea4f57)


## 🏗️ Installation  

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/prajesdas/Smart-Parking-Space-Detector-using-YOLO-and-OpenCV.git
cd Smart-Parking-Space-Detector-using-YOLO-and-OpenCV
```

### 2️⃣ Install Dependencies  
```sh
pip install -r requirements.txt
```

### 3️⃣ Download YOLO Weights  
- Download YOLOv4 weights from [official YOLO website](https://pjreddie.com/darknet/yolo/) or use a pre-trained YOLOv8 model.  
- Place the weights in the `models/` directory.  

### 4️⃣ Run the Detection Script  
```sh
python detect_parking.py --source video.mp4
```
or for live webcam feed:  
```sh
python detect_parking.py --source 0
```

## 📂 Project Structure  
```
📂 Smart-Parking-Space-Detector  
 ┣ 📂 models/              # YOLO model weights  
 ┣ 📂 data/                # Parking lot images/videos  
 ┣ 📂 utils/               # Helper functions  
 ┣ 📜 detect_parking.py    # Main script for detection  
 ┣ 📜 requirements.txt     # Dependencies  
 ┣ 📜 README.md            # Project documentation  
```

## 🚀 Future Enhancements  
🔹 Integration with a **mobile app** for user-friendly access 📱  
🔹 Adding a **cloud database** to store parking statistics ☁️  
🔹 Implementing **number plate recognition** for security 🔢  

## 🤝 Contributing  
Pull requests are welcome! If you'd like to contribute, please open an issue first to discuss your ideas.  

## 📜 License  
This project is **MIT Licensed**. Feel free to use and modify it.  

## 📧 Contact  
For any queries, reach out to **Prajes Das** via GitHub.  

🔗 [GitHub Repository](https://github.com/prajesdas/Smart-Parking-Space-Detector-using-YOLO-and-OpenCV)  
