# 🖼️ AI Image Classifier

This project is a simple yet powerful **AI Image Classifier** built using **Streamlit**, **TensorFlow Keras**, and the **MobileNetV2** model pre-trained on the ImageNet dataset.

It allows users to upload an image, processes it using deep learning, and returns the top 3 predictions of what the image might be.

---

## 🚀 Demo

<img src = "SS.png" alt = "Screenshot">

---

## 📸 Features

- 🧠 Uses **MobileNetV2**, a lightweight CNN model trained on ImageNet.
- 🖼️ Allows image uploads in `.jpg` and `.png` formats.
- 🔄 Preprocesses the image for optimal classification results.
- 📈 Displays the **top 3 predictions** with probability scores.
- 🌐 Built with **Streamlit** for interactive, web-based UI.

---

## 🛠️ Installation

1. Clone this repository:

```bash
git clone https://github.com/KunalxKushwaha/Image-Classifier.git
cd Image-Classifier
pip install -r requirements.txt
streamlit run app.py
```

## 📂 Project Structure
image-classifier/
├── app.py                # Main Streamlit app file
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation

## 🌟 Uniqueness of the Project
✅ 1. Real-Time AI in the Browser
The project bridges the gap between powerful AI models and non-technical users by enabling real-time image classification directly in the browser — no command-line, no heavy setup.

✅ 2. Zero Training Required (Transfer Learning)
Uses a pre-trained MobileNetV2 model via Keras — showcasing the power of transfer learning without needing a huge dataset or GPU for training.

✅ 3. Streamlit-Powered Interface
Most machine learning models are command-line or Jupyter-based. This project wraps the AI model in a responsive, interactive UI using Streamlit — making it accessible, sharable, and deployable.

✅ 4. Minimal Yet Modular
Clean, modular code allows easy extension:

Add Grad-CAM visualizations

Replace with custom-trained models

Support for drag-and-drop or batch uploads

✅ 5. Efficient and Lightweight
MobileNetV2 is known for speed and small size — perfect for edge devices, low-latency apps, or when performance matters.

✅ 6. Error-Handled UX
Includes built-in error handling, spinners, and friendly UI prompts — making it robust for users who are new to AI tools.

## 💼 Use Cases of the Project
This project can be the foundation for several real-world applications:

🎓 1. Educational Tool
Demonstrates the practical application of deep learning and transfer learning.

Perfect for workshops, AI bootcamps, and introductory ML courses.

🧪 2. Quick Prototyping
AI researchers and developers can test pre-trained models or build MVPs for image classification tasks without worrying about the UI.

📦 3. AI-Powered Product Classifier
With minimal tweaks, this can be turned into a:

Fashion item recognizer

Grocery product scanner

Artwork identifier

🧠 4. AI Portfolio Project
A great showcase for ML enthusiasts or job-seekers to demonstrate:

Model integration

Web UI development

End-to-end deployment understanding

🌍 5. Community or Client Demos
Quickly share the model’s functionality with clients, teammates, or stakeholders without setting up a development environment.

📱 6. Lightweight Mobile Deployments
Since MobileNetV2 is optimized for mobile and edge devices, this project could be ported to mobile apps or embedded systems.

🚀 7. Base for Custom Training Pipelines
You can replace the pre-trained model with a custom-trained CNN for:

Medical image diagnosis

Wildlife image detection

Industrial defect detection

# Author- Kunal Kushwaha✒️
