# 🧴 AI-Based Skin Oiliness Detection and Skincare Recommendation System

We’ve developed a cutting-edge system that uses deep learning and computer vision to predict skin oiliness levels and classify skin types from facial images. The system accurately detects whether a person has oily or non-oily skin, providing key insights for personalized skincare and product recommendations.

## 🔑 Key Features

- **Real-time Face Detection**: Using OpenCV and Haar Cascade Classifier.
- **Deep Learning Model**: Built on VGG16 transfer learning, fine-tuned for skin oiliness prediction.
- **Data Augmentation**: Applied rotation, flipping, brightness adjustments, and zooming to improve model performance.
- **Live Video Processing**: Detect faces, classify skin oiliness levels (Low, Normal, Middle, High), and deliver instant results.
- **Personalized Skincare Recommendations** based on oiliness levels.

## 🛠️ Technologies Used

- Python
- TensorFlow & Keras
- OpenCV
- NumPy
- Matplotlib
- VGG16 (Transfer Learning)
- Fully Connected Layers
- ImageDataGenerator for Data Augmentation

## 💡 Project Goal

This project blends AI and skincare to offer users customized recommendations for better skin health. By using facial analysis, it supports a smarter approach to skincare product selection and routines.

## 🚀 Getting Started

1. Clone the repository
2. Install dependencies using `pip install -r requirements.txt`
3. Run the application and point the webcam to detect and classify

```bash
git clone https://github.com/your-username/skin-oiliness-detector.git
cd skin-oiliness-detector
python app.py
```

## 📄 License

This project is licensed under the MIT License.