# 🌟 Task Instructions

1. Train an image recognition model using **Teachable Machine** by Google. Use at least two classes and evaluate the model.
2. Download the trained model in **TensorFlow → Keras** format.
3. Write a Python script that loads the model, accepts an input image, and predicts its class.
4. Submit the Python script, the exported model files, and a screenshot of the output.

## ✨ Solution

### 1. 🛠️ Train the Model with Teachable Machine

1. Go to [Teachable Machine – Image Project](https://teachablemachine.withgoogle.com/train/image).
2. Click **Get Started** → **New Project** → **Standard Image Model**.
3. Create two classes:
   - 🐶 **Class 1:** Dog
   - 🐱 **Class 2:** Cat
4. Upload at least two image samples for each class.
5. Click **Train Model** and wait for training to finish.
6. Use the **Preview** panel to test the model:
   - Upload an image from your files, or drag and drop it directly into the preview window.

<img width="958" height="414" alt="Teachable Machine training and preview" src="https://github.com/user-attachments/assets/ec5568c9-5187-4611-b133-9239c6b1019a" />

---
1️
### 2. 📊 Test the Model in Google Colab

1. Open [Google Colab](https://colab.research.google.com/) and paste in the provided code (see `Python script`).
2. Upload the following exported files:
   - `keras_model.h5`
   - `labels.txt`
   - A sample test image
3. Click **Run** to execute the script and confirm there are no errors.

<img width="958" height="345" alt="image" src="https://github.com/user-attachments/assets/18c69624-a7e4-4b58-8524-820a904d6947" />

