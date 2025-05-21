# Advance-Knee-Osteoarthritis-Detection-and-Severity-Prediction
Deep learning project using ResNet50 to detect and predict knee osteoarthritis severity. Achieved 81.2% accuracy and reduced computational time by 30% through data preprocessing and augmentation. Built with Python, TensorFlow, and deep learning techniques.

# Knee Osteoarthritis Detection Web App

This project is a Deep Learning-based web application designed to detect Knee Osteoarthritis (OA) severity using medical images. The app uses a trained model to classify the Kellgren-Lawrence (KL) grade of knee OA from X-ray images.

## 🧠 Tech Stack

- Python
- TensorFlow / Keras
- Streamlit
- OpenCV
- NumPy, Pandas
- PIL
- scikit-learn

## 📁 Project Structure

knee_OA_dl_app/
│
├── app.py # Main Streamlit web app
├── model/
│ └── knee_model.h5 # Pre-trained deep learning model
├── utils/
│ ├── helper.py # Image preprocessing and prediction functions
│ └── config.py # Configuration settings
├── images/
│ └── example.jpg # Sample knee X-ray image
├── requirements.txt # List of Python dependencies
└── README.md # Project documentation

bash
Copy code

## 🚀 Features

- Upload X-ray images and get OA prediction
- Visual KL grade classification output
- Simple and interactive web interface
- Model built with deep learning (CNN)

## 🔧 Installation & Setup

Follow these steps to run the project locally:

### 1. Clone the Repository or Unzip

If using GitHub:

```bash
git clone https://github.com/your-username/knee_OA_dl_app.git
cd knee_OA_dl_app
Or, if you downloaded this ZIP, unzip and navigate to the folder.

2. Create a Virtual Environment (optional but recommended)
bash
Copy code
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
3. Install Dependencies
bash
Copy code
pip install -r requirements.txt
4. Run the Streamlit App
bash
Copy code
streamlit run app.py
The app will open in your default browser at http://localhost:8501.

🖼️ Example Output
Upload a sample X-ray image and receive KL Grade (0–4) with explanation.

📌 Notes
Ensure you have Python 3.7+ installed.

The model (knee_model.h5) must be placed in the model/ directory.

If you're adding new test images, place them in the images/ folder or upload directly via the UI.
