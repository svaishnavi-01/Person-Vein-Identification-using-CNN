Person Vein Identification using CNN
📌 Project Overview

This project implements a Person Vein (Finger Vein) Identification System using Convolutional Neural Networks (CNN) for feature extraction and Machine Learning classification.
Vein-based biometrics are highly secure because vein patterns are internal and unique to each person.

🛠 Technologies Used

Python

OpenCV

TensorFlow / Keras

NumPy

Scikit-learn

Matplotlib

📁 Project Structure
FingerVein/
│── Dataset/              # Dataset folder (not uploaded to GitHub)
│── images/               # Output images
│── model/                # Trained model files
│── testImages/           # Images for testing
│── FingerVein.py         # Main Python file
│── run.bat               # Run file (Windows)
│── requirements.txt
│── README.md

📥 Dataset Information

The dataset is not included in this repository due to size limitations.

Dataset Folder Structure:
Dataset/
│── vein001_1/
│── vein002_1/
│── vein003_1/


Place the dataset inside the Dataset folder exactly as shown above.

⚙️ Installation Steps
1️⃣ Clone the repository
git clone https://github.com/svaishnavi-01/Person-Vein-Identification-using-CNN.git
cd Person-Vein-Identification-using-CNN

2️⃣ Create a virtual environment (recommended)
python -m venv venv
venv\Scripts\activate

3️⃣ Install required libraries
pip install -r requirements.txt

▶️ How to Run the Project
Option 1: Run using Python
python FingerVein.py

Option 2: Run using batch file (Windows)
run.bat

🧪 Testing the System

Place test finger vein images in the testImages folder

Run the project

The system will identify the person based on vein patterns

📊 Output

Displays the processed vein image

Shows the predicted person identity

🚀 Future Enhancements

Web-based interface

Real-time camera input

Improved accuracy with larger datasets

Deep learning optimization

👩‍💻 Author

Vaishnavi Samaleti
B.Tech – Computer Science & Engineering (Data Science)

📜 License

This project is developed for academic and educational purposes.
