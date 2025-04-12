# ✍️ ScribbleSync - Handwriting Recognition for SLD Learners

ScribbleSync is an assistive educational tool designed to help children with Specific Learning Disabilities (SLD)
improve their handwriting. It combines an intuitive digital canvas interface with a machine learning backend that recognizes handwritten characters based on stylus/finger strokes and pressure.

---

## 🚀 Features

- ✒️ Interactive canvas for writing using finger/stylus
- 🎚️ Stroke pressure simulation (if hardware-supported)
- 🖼️ Converts strokes to grayscale image with pressure-based thickness
- 🧠 CNN-based handwriting recognition trained on the EMNIST dataset
- 🧩 Backend API for real-time predictions
- 💡 Designed for adaptive learning and skill-building

---

## 🌐 Frontend

The frontend is a responsive web interface that allows children to draw characters.

### Tech Used:
- HTML, CSS, JavaScript
- Canvas API for drawing
- Axios or Fetch API for sending stroke data to the backend

### Key Features:
- 🖊️ Real-time drawing on canvas
- 📤 JSON-based stroke data capture (x, y, pressure)
- 🔁 Displays predicted character returned by backend


🧠 Backend
Built with Flask, the backend handles stroke-to-image conversion and character prediction.

Tech Used:
  Python + Flask
  TensorFlow / Keras (for model)
  PIL, NumPy, SciPy

🧪 ML Model

Dataset: EMNIST Balanced

Model: CNN trained on 28x28 grayscale images

Inputs: Normalized images with optional pressure-based stroke width

👥 Team ScribbleSync
Kanimozhi   – Frontend & Canvas Drawing Logic
Kannishka   – Website Design + Research
Manisha     – Integration & UX
Ranjit      - Flask & Backend
Prathikshaa - Database Manager
Meyyappan   – ML, Model Tuning

🙌 Acknowledgements
      EMNIST Dataset

      TensorFlow & Keras

      Flask API framework

