# 🚁 Drone Detection with Custom Dataset

This project implements a **drone detection system** using a custom-labeled dataset. It aims to identify drones in aerial imagery using object detection techniques.

---

## 🎯 Objective

Detect and classify **drones** from images or video streams using a trained machine learning model. Ideal for security, surveillance, or airspace monitoring purposes.

---

## 📁 Project Structure

```
Drone-Detection/
│
├── drone0.ipynb                      # Main notebook for model training/testing
├── drone_dataset/
│   ├── data.yaml                     # Dataset configuration file for YOLO format
│   ├── train/                        # Training images and labels
│   └── valid/                        # Validation images and labels
├── LICENSE
└── README.md
```

---

## 📸 Sample Outputs

Sample outputs of drone detection:

![D1](https://user-images.githubusercontent.com/111522957/197338718-16110884-7c6b-4e52-93d9-815f895d8bf3.png)

![D2](https://user-images.githubusercontent.com/111522957/197338722-8844eba2-437f-4e51-a228-a4baa07a3867.png)

![D3](https://user-images.githubusercontent.com/111522957/197338724-58644b9a-5214-4f01-81ee-2d78bcddfa7e.png)

---

## 🚀 How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/Drone-Detection.git
   cd Drone-Detection
   ```

2. **Install Requirements**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**:
   Open the notebook and run:
   ```bash
   jupyter notebook drone0.ipynb
   ```

---

## ⚙️ Dataset Format

The dataset follows the **YOLO format**, containing:
- `.jpg` images in `train/` and `valid/`
- `.txt` annotation files with bounding box labels

Ensure that `data.yaml` correctly defines the dataset path and class names.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙌 Acknowledgments

- Object detection methods inspired by YOLO
- Open drone image datasets


***Altan Ulaş Zöhre***
