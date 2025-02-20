
### **Road Lane Line Detection 🚗🛣️**  
*A computer vision project for detecting road lane lines using OpenCV and deep learning.*

## **📌 Overview**  
Road Lane Line Detection is a computer vision project that identifies lane markings in real-time from video or images. This technology is widely used in autonomous vehicles and advanced driver-assistance systems (ADAS).  

## **🛠 Features**
✅ Detect lane lines from images and videos  
✅ Uses OpenCV for image processing  
✅ Can be extended with deep learning for better accuracy  
✅ Works with different road conditions  
              

## **📸 Demo**
🔹 **Input Image:**  
![Input Road](https://github.com/G-KINGSTON/Road_Lane_Line_Detection_Project/blob/main/LANE_TEST.jpeg?raw=true)  
🔹 **Detected Lane Lines:**  
![Output Lane](https://github.com/G-KINGSTON/Road_Lane_Line_Detection_Project/blob/main/OUTPUT.png?raw=true)  

## **🛠 Installation**
1️⃣ Clone the repository:  
```bash
git clone https://github.com/your-username/road-lane-detection.git
cd road-lane-detection
```
2️⃣ Install dependencies:  
```bash
pip install -r requirements.txt
```
3️⃣ Run the detection script:  
```bash
python main.py --input video.mp4
```

## **📖 How It Works**
- **Grayscale Conversion**: Converts the image to grayscale  
- **Gaussian Blur**: Reduces noise  
- **Edge Detection**: Uses Canny edge detection  
- **Region Masking**: Focuses on the road area  
- **Hough Transform**: Detects lane lines  

## **🚀 Future Improvements**
🔹 Implement deep learning-based lane detection  
🔹 Support for curved lanes  
🔹 Integrate with self-driving car simulations  
