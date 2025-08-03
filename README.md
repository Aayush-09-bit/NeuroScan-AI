🧠 AI Brain Tumor Detection System
An AI-powered web application that detects and classifies brain tumors from MRI images using deep learning with 97% accuracy.

![Brain Tumor Detection](https://img.shields.io/badge/python-v3.8+-blue.svg)
![flask](https://img.shields.io/badge/flask-v2.0+-red.svg)
![tensorflow](https://img.shields.io/badge/tensorflow-v2.0+-orange.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

🎯 Overview
This system uses VGG16 transfer learning to classify brain MRI scans into four categories:

Glioma - Primary brain tumor from glial cells
Meningioma - Tumor from brain protective membranes
Pituitary - Tumor affecting hormone production
No Tumor - Healthy brain tissue

✨ Features

🤖 97% Accuracy - VGG16-based CNN model
🌐 Web Interface - Modern Flask application
📱 Responsive Design - Works on all devices
⚡ Real-time Analysis - Instant MRI scan processing
🎨 Modern UI - Glassmorphism design with animations

🚀 Quick Start

1. Clone and setup

(bash)
git clone https://github.com/yourusername/brain-tumor-detection.git
cd brain-tumor-detection
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

2. Install dependencies

(bash)
pip install -r requirements.txt

3. Run the application

(bash)
python main.py

4. Open browser → http://localhost:5000

📊 Model Performance

| Class       | Precision | Recall | F1-Score |
|-------------|-----------|--------|----------|
| Glioma      | 98%       | 90%    | 94%      |
| Meningioma  | 90%       | 98%    | 94%      |
| Pituitary   | 100%      | 100%   | 100%     |
| No Tumor    | 99%       | 97%    | 98%      |
| Overall     | 97%       | 96%    | 96%      |

📁 Project Structure

brain-tumor-detection/
├── main.py              # Flask application
├── models/model.h5      # Trained ML model
├── static/              # CSS, images
├── templates/           # HTML templates
├── uploads/             # Temporary storage
└── requirements.txt     # Dependencies

🔧 Technical Details

Architecture: VGG16 + Custom classification head
Input Size: 128x128x3 RGB images
Training: Transfer learning with data augmentation
Framework: TensorFlow/Keras + Flask

🤝 Contributing

Fork the repository
Create feature branch (git checkout -b feature/improvement)
Commit changes (git commit -m 'Add improvement')
Push to branch (git push origin feature/improvement)
Open Pull Request

⚠️ Medical Disclaimer
For educational purposes only. Not a substitute for professional medical diagnosis. Always consult qualified medical professionals.

📜 License
MIT License - see LICENSE file for details.