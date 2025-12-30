# Real-Time Sign Language Interpreter

**A Computer Vision application that translates hand gestures into text instantly.**

This project utilizes deep learning and computer vision to bridge the communication gap for the hearing impaired. It captures video from the webcam, tracks hand landmarks, and classifies the gestures into Alphabets, Numbers, or common words (like "Hello", "Bye").

---

## 🌟 Key Features

* **Live Recognition:** Real-time translation from the webcam feed.
* **Comprehensive Dictionary:**
    * **Alphabets:** A-Z recognition.
    * **Numbers:** 0-9 recognition.
    * **Common Phrases:** Recognizes gestures for "Hello", "Bye", "Okay", etc.
* **Visual Feedback:** Displays the recognized text overlay on the screen alongside the camera feed.

---

## 🛠️ Tech Stack

* **Language:** Python
* **Computer Vision:** OpenCV (cv2), MediaPipe (for hand landmark detection)
* **Machine Learning:** Keras 
* **Data Processing:** NumPy

---

## 📂 Note on Dataset

> **Note:** The raw training dataset (containing thousands of hand images in the `data/` folder) has been **excluded** from this repository to minimize file size.
>
> The project includes the **pre-trained model**, so the application functions immediately without needing to retrain on the dataset.

---

## 🚀 Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Harshitmishra09/YOUR-REPO-NAME.git](https://github.com/Harshitmishra09/YOUR-REPO-NAME.git)
    ```
2.  **Navigate to the directory:**
    ```bash
    cd YOUR-REPO-NAME
    ```
3.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Run the Interpreter:**
    ```bash
    python SLD.py
    ```

---

## 🎮 How to Use
1.  Launch the application.
2.  Hold your hand up to the webcam.
3.  Perform a sign (e.g., show '5' or sign 'A').
4.  The system will display the predicted character/word on the screen.

---

**Developed by Harshit Mishra**
