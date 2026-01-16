# 🚗 Vehicle Headlight Detection Using OpenCV

This project implements a **vehicle headlight detection system** using **Python and OpenCV**.  
It processes road images to detect bright regions corresponding to vehicle headlights, which is especially useful for **night-time driving analysis** and **traffic safety research**.

---

## 🚀 Features

- Image-based vehicle headlight detection
- Converts images to grayscale for easier processing
- Noise reduction using blurring techniques
- Thresholding to isolate bright headlight regions
- Contour detection for identifying light sources
- Simple and educational computer vision workflow

---

## 🧠 Tech Stack

- Python 3.10+
- OpenCV
- NumPy
- Matplotlib (for visualization)

---

## 📦 Installation

### 1️⃣ Clone the Repository
bash
git clone https://github.com/your-username/vehicle-headlight-detection.git
cd vehicle-headlight-detection
## 2️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
## ▶️ Usage
Place your input images in the project directory
Update image paths in headlightDetection.py
python headlightDetection.py
The program will: Display original and processed images
Detect contours representing headlights
Save intermediate outputs (grayscale, blurred images)

## 📂 Project Structure
vehicle-headlight-detection/
│
├── headlightDetection.py
├── requirements.txt
├── runtime.txt
├── bus_coming.jpg
├── going.jpg
└── both.jpg

## 🎯 Learning Outcomes
Understanding image preprocessing in OpenCV

Working with grayscale, blur, and threshold operations

Contour detection and centroid calculation

Real-world computer vision problem solving

## 🔮 Future Enhancements
Real-time video headlight detection

Headlight intensity classification

Machine learning-based detection

Integration with driver assistance systems

## 👨‍💻 Author
Atul Anand
BCA (Hons)
Amity University, Noida

## ⭐ Support
If you find this project useful, don’t forget to star ⭐ the repository!
