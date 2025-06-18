
# VideoQA with QwenVL 🚀

VideoQA with QwenVL is a cutting-edge project for video and image question answering using the powerful Qwen/Qwen2-VL-7B-Instruct model. This repository provides everything you need to get started with multimodal QA, including model setup, video frame extraction, and efficient inference workflows. The code is modular, easy to extend, and ready for both research and practical applications.

---

## 📁 Project Structure

- **QwenVL_Finetune.ipynb**: Main notebook for model setup, video frame extraction, and inference.
- **QwenVLInference.ipynb**: Additional notebook for inference tasks (see inside for details).
- **data/**: Contains CSV files for various video QA tasks:
  - `action.csv`, `count.csv`, `frameqa.csv`, `transition.csv`: Datasets for different question types.
  - `desktop.ini`: System file (can be ignored).

---

## ✨ Features

- End-to-end pipeline for both image and video question answering.
- Loads and configures Qwen2-VL-7B-Instruct with advanced quantization (4-bit, AWQ) for efficient inference.
- Fast video frame extraction using PyAV and NumPy.
- Modular code for easy adaptation to new datasets or tasks.
- Ready-to-run Jupyter notebooks for reproducible experiments.
- Example datasets and sample code for quick experimentation.

---

## 🚦 Quick Start

1. **Open** `QwenVL_Finetune.ipynb` in Jupyter or VS Code.
2. **Run** the first cell to install all required packages automatically.
3. **Follow** the notebook cells to load the model, process video/image data, and perform inference.
4. **Customize** the `data/` folder to add or modify datasets for your own experiments.

---


## 🛠️ Requirements

- Python 3.8+
- Jupyter Notebook or VS Code
- GPU recommended for best performance

All dependencies can be installed with:

```powershell
pip install -r requirements.txt
```

---


