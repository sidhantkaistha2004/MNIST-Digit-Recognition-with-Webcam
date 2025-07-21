<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png" width="400" alt="MNIST Digits Example"/>
</p>

<h1 align="center">🖐️ MNIST Digit Recognition with Webcam 🎥</h1>

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/python-3.7--3.10-blue?logo=python"/></a>
  <a href="https://www.tensorflow.org/"><img src="https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow"/></a>
  <a href="https://opencv.org/"><img src="https://img.shields.io/badge/OpenCV-4.x-green?logo=opencv"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow.svg"/></a>
</p>

---

> **Real-time handwritten digit recognition using a webcam, powered by a CNN trained on MNIST.**
> 
> ✍️ Works with digits written in black or white, on any background!

---

## 🚀 Features

- 🧠 **Train a CNN** on the MNIST dataset (or use the pre-trained model)
- 🎥 **Real-time digit prediction** using your webcam (from within the notebook)
- 🖤🤍 **Robust to digit color and background**
- 🪄 **Prediction result overlays** directly on the camera window
- 🔁 **Predict as many times as you want** (SPACE to predict, ESC to exit)
- 📊 **Visualize correct and incorrect predictions** from the test set

---

## 📦 Requirements

- Python 3.7–3.10 (recommended)
- [TensorFlow](https://www.tensorflow.org/)
- [OpenCV](https://opencv.org/)
- numpy < 2.0
- matplotlib

Install all dependencies:
```sh
pip install tensorflow opencv-python numpy<2 matplotlib
```

> **⚠️ Note:** If you see errors about NumPy, downgrade it:
> ```sh
> pip install "numpy<2"
> ```

---

## 📁 Files

| File                          | Purpose                                             |
|-------------------------------|-----------------------------------------------------|
| `mnist_digit_recognition.ipynb` | Jupyter notebook for training, prediction, and visualization |
| `model.h5`                    | Saved model (created after training)                |

---

## 🛠️ Usage

### 1️⃣ Open the Notebook
Open `mnist_digit_recognition.ipynb` in Jupyter Notebook or JupyterLab and run all cells. This will:
- Train the model (or skip if `model.h5` exists)
- Evaluate accuracy
- Show example test images with correct and incorrect predictions
- Allow you to use your webcam for real-time digit prediction (SPACE to predict, ESC to exit)

> **Note:** Webcam code works only in a local Jupyter environment (not on Colab or remote servers).

---

## 🧩 Troubleshooting

- **NumPy errors:** Downgrade numpy as shown above.
- **Camera not detected:** Make sure your webcam is connected and not used by another app.
- **TensorFlow errors:** Ensure you are using a compatible Python version (3.7–3.10 recommended).
- **Webcam:** Must be run locally, not on Colab or remote servers.

---

## 📸 Example

<img width="634" height="508" alt="Screenshot 2025-07-21 104739" src="https://github.com/user-attachments/assets/69ea7501-8f4e-4f08-917c-da95ae6e1e65" />


---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
