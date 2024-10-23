# 🚀 Real-Time Human Detection & Counting

A TensorFlow-based `Faster RCNN Inception v2` model for detecting and counting humans in real-time using images, videos, and live camera feeds. This project leverages a pre-trained `frozen_inference_graph.pb` for efficient detection and visualization of human counts, providing insights through Enumeration and Accuracy plots.

---

## 📋 Features

- **Real-Time Detection**: Supports detecting humans from images, video files, and live camera feeds.
- **Pre-Trained Model**: Uses a `frozen_inference_graph.pb` for faster and more accurate detection.
- **Visual Analysis**: Generates detailed plots for:
  - **Enumeration Plot**: Shows human count over time.
  - **Avg. Accuracy Plot**: Displays average detection accuracy over time.
- **Crowd Report Generation**: Generates a PDF report with information on max human count, accuracy, and a brief crowd status analysis.

---

## 📌 Requirements

- Python 3
- `tkinter`
- `messagebox`
- `PIL`
- `cv2` (OpenCV)
- `argparse`
- `matplotlib`
- `numpy`
- `time`
- `os`
- `tensorflow`
- `fpdf`

---

## 🚀 How It Works

1. **Setup**: Download the project files and run `main.py` on your local machine.
2. **Start the Application**: On the startup window, choose between `START` to begin or `EXIT` to close the application.
3. **Choose Detection Method**:
   - **Detect from Image**: Select an image file, preview it, and click `DETECT` to start detection.
   - **Detect from Video**: Select a video file, preview it, and click `DETECT` to start detection.
   - **Detect from Camera**: Click `OPEN CAMERA` to begin real-time detection through your camera.
4. **View Results**:
   - Once detection is complete, two plots are displayed:
     - **Enumeration Plot**: Human Count vs. Time.
     - **Avg. Accuracy Plot**: Avg. Accuracy vs. Time.
   - Option to generate a **Crowd Report** as a PDF, which is saved automatically in the project directory.

---

## 📌 Purpose

This script helps users to easily detect and count humans in real-time through images, videos, or live camera feeds. It also provides a detailed crowd analysis through a report, making it useful for monitoring environments, events, or areas with human activity.

---

### 📌Compilation Steps

- Install all the required libraries.
- After that download the code file, and run main.py on local system.
- Then the script will start running and user can explore it by detecting the human and also getting the count of it.

---

### 📌SCREENSHOTS

<p align="center">
  <img width = 1000 src="Screenshots/1.jpg" /><br>
  <img width = 1000 src="Screenshots/2.jpg" /><br>
</p>

- #### Image:

<p align="center">
  <img width = 1000 src="Screenshots/3.jpg" /><br>
  <img width = 1000 src="Screenshots/4.jpg" /><br>
  <img width = 1000 src="Screenshots/5.jpg" /><br>
  <img width = 1000 src="Screenshots/6.jpg" /><br>
  <img width = 1000 src="Screenshots/7.jpg" /><br>
  <img width = 1000 src="Screenshots/8.jpg" /><br>
  <img width = 1000 src="Screenshots/9.jpg" /><br>
  <img width = 1000 src="Screenshots/10.jpg" /><br>
  <img width = 1000 src="Screenshots/11.jpg" /><br>
  <img width = 1000 src="Screenshots/12.jpg" /><br>
</p>

- #### Video:

<p align="center">
  <img width = 1000 src="Screenshots/13.jpg" /><br>
  <img width = 1000 src="Screenshots/14.jpg" /><br>
  <img width = 1000 src="Screenshots/15.jpg" /><br>
  <img width = 1000 src="Screenshots/16.jpg" /><br>
  <img width = 1000 src="Screenshots/17.jpg" /><br>
</p>

- #### Camera:

<p align="center">
  <img width = 1000 src="Screenshots/18.jpg" /><br>
  <img width = 1000 src="Screenshots/19.jpg" /><br>
  <img width = 1000 src="Screenshots/20.jpg" /><br>
  <img width = 1000 src="Screenshots/21.jpg" /><br>
  <img width = 1000 src="Screenshots/22.jpg" /><br>
  <img width = 1000 src="Screenshots/23.jpg" /><br>
</p>

---

### 📌 Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug fixes, feel free to open an issue or submit a pull request.
