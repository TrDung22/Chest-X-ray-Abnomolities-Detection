# Chest X-ray Abnormalities Detection

This project focuses on detecting abnormalities in chest X-rays using the YOLOv8 model and is deployed as a web application via Flask.

## 🎯 Objective

To assist healthcare professionals in quickly and conveniently identifying abnormalities in patients' chest X-rays, enhancing the capability for accurate medical diagnosis.

![Demo](assets/screen.gif)

## 📦 Data Source

- The project utilizes data from VinBigData.

## 🚀 Usage

1. **Start the Application**:

    ```
    python predict_api.py
    ```

2. **Access the Application**:

    Open a browser and navigate to `http://127.0.0.1:5000`.

3. **Upload and Analyze**:
    
    - Drag and drop or select the chest X-ray image you wish to analyze.
    - Click 'Upload file' to initiate the analysis and view the results.

## ⚙️ Installation

1. **Requirements**:

    - Python 3.x
    - Libraries: flask, yolov8, ...

2. **Setup**:

    ```
    git clone https://github.com/TrDung22/Chest-X-ray-Abnomolities-Detection.git
    pip install -r requirements.txt
    ```

## 🌐 Interface

- **Home Page**:

  Here, users can upload X-ray images and receive analysis results.

- **Image Analysis**:

  The uploaded image is analyzed by the YOLOv8 model, with results promptly displayed on the web page.

## 💡 Notes

- Ensure the uploaded image is in the right format and not oversized.
- The application is optimized primarily for chest X-rays.
