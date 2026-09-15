# 🖼️ AI Image Classifier

A web app built with **Streamlit** and **MobileNetV2** (pre-trained on ImageNet) to classify user-uploaded images in real time.

## Features
- Pre-trained MobileNetV2 deep learning model.
- Interactive Streamlit UI for uploading images (.jpg, .png).
- Top-3 class predictions with confidence percentages.

## How to Run Locally

1. Clone the repo:
   git clone https://github.com/secret-lettuce27/ai_image_classifier.git
   cd ai_image_classifier


2. Run the app:
   A. using uv (recommended)
      uv run streamlit run main.py
   B. using pip
      pip install -r requirements.txt
      streamlit run main.py
