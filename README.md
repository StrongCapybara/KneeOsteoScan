# KneeOsteoScan

**KneeOsteoScan** is a web-based application developed to assist in the early detection and classification of knee osteoarthritis using X-ray images. This project was undertaken as **Project 2** during my B.Tech at Vellore Institute of Technology (VIT).

## 🩺 Project Overview

Knee osteoarthritis (OA) is a prevalent degenerative joint disease that can lead to significant discomfort and mobility issues. Early detection is crucial for effective management and treatment. KneeOsteoScan leverages deep learning techniques to analyze knee X-ray images, aiming to classify the severity of osteoarthritis, thereby aiding medical professionals in diagnosis and treatment planning.

## 🚀 Features

- **User-Friendly Interface**: Upload knee X-ray images through a simple web interface.
- **Automated Analysis**: Backend powered by a trained deep learning model to assess and classify OA severity.
- **Real-Time Results**: Instantaneous feedback on the uploaded images.
- **Secure and Efficient**: Ensures user data privacy and delivers rapid analysis.

## 📊 Model Training and Dataset
The deep learning model was trained on a curated dataset of knee X-ray images, annotated for varying degrees of osteoarthritis severity. The training process involved:

- **Data Preprocessing**: Normalization, resizing, and augmentation of images.
- **Model Architecture**: Utilized a convolutional neural network (CNN) optimized for image classification tasks.
- **Evaluation Metrics**: Accuracy, precision, recall, and F1-score were used to assess model performance.

*Note*: Due to data privacy concerns, the dataset is not included in this repository.


## 🧠 Technology Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Python (Flask framework)
- **Machine Learning**: TensorFlow/Keras for model development and training
- **Deployment**: Local server setup; adaptable for cloud deployment

## ⚙️ Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/StrongCapybara/KneeOsteoScan.git
   cd KneeOsteoScan

2. **Create a Virtual Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt

4. **Run the Application**:
   ```bash
   python app.py

5. **Access the Web Interface**:

    Open your browser and navigate to http://127.0.0.1:5000/ to use the application.


## 📄 License
This project is licensed under the MIT License.

## 🙏 Acknowledgements
- [Dr. Mohiul Islam](https://www.linkedin.com/in/dr-mohiul-islam-81604070/): Project Guide at Vellore Institute of Technology (VIT), for his guidance and support.
- Open-source contributors and the machine learning community for their resources and inspiration.
