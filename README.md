# 🚗 Vehicle Counter Using OpenCV

## 📌 Overview

This project is a **Vehicle Counter** built using **Python**, **OpenCV**, and **NumPy**. It detects moving vehicles from a pre-recorded video using **background subtraction** and counts the number of vehicles crossing a predefined counting line.

The project demonstrates the fundamentals of computer vision, including motion detection, contour detection, object tracking, and real-time vehicle counting.

---

## ✨ Features

* Detects moving vehicles from a video.
* Uses background subtraction for motion detection.
* Draws bounding boxes around detected vehicles.
* Tracks the center point of each detected vehicle.
* Counts vehicles as they cross a predefined line.
* Displays the live vehicle count on the video.

---

## 🛠️ Technologies Used

* Python 3.x
* OpenCV
* NumPy

---

## 📂 Project Structure

```text
Vehicle_Counter/
│
├── vehicle_counter.py      # Main Python script
├── video.mp4               # Input video
├── requirements.txt        # Project dependencies
├── README.md               # Project documentation
└── .gitignore              # Git ignore file
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/Vehicle-Counter.git
```

### 2. Navigate to the project directory

```bash
cd Vehicle-Counter
```

### 3. Install the required packages

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Execute the following command:

```bash
python vehicle_counter.py
```

The application will open the input video, detect moving vehicles, and display the total vehicle count in real time.

---

## ⚙️ How It Works

1. Reads frames from the input video.
2. Converts each frame to grayscale.
3. Applies Gaussian Blur to reduce noise.
4. Uses Background Subtraction (MOG) to detect moving objects.
5. Performs morphological operations to improve detection.
6. Finds contours of moving vehicles.
7. Draws bounding boxes around detected vehicles.
8. Calculates the center of each detected vehicle.
9. Counts vehicles when their center crosses the counting line.
10. Displays the updated vehicle count on the video.

---

## 📦 Dependencies

* OpenCV (opencv-contrib-python)
* NumPy

Install them using:

```bash
pip install opencv-contrib-python numpy
```

---

## 📈 Future Improvements

* Support live CCTV camera feeds.
* Detect and count multiple vehicle categories (car, bus, truck, bike).
* Improve tracking using DeepSORT or ByteTrack.
* Integrate YOLO for more accurate object detection.
* Generate traffic analytics and reports.
* Store vehicle counts in a database.

---

## 📸 Sample Output

You can add screenshots of the running application inside an `images/` folder and display them here.

Example:

```text
images/
├── output1.png
├── output2.png
```

---

## 👨‍💻 Author

**Arunish Shivam**

Computer Science Engineer | AI & Machine Learning Enthusiast

