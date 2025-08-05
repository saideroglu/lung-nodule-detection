# lung-nodule-detection
This project focuses on detecting lung nodules from CT (Computed Tomography) scans using deep learning techniques. It was developed as a graduation thesis for the Computer Engineering Department at Yildiz Technical University.

---

## Dataset

This project utilizes the **LUNA16 dataset**, which contains CT scans for lung nodule detection.

**Note:** Due to file size, the dataset is not included in this repository.

[LUNA16 Dataset Link](https://luna16.grand-challenge.org/)

---

## Environment

- **Language:** Python 3  
- **Platform:** Google Colab (Jupyter Notebook)

---

## How to Run

Since the code is developed on Google Colab, some output cells might not be visible in the `.ipynb` files. You can open and run each notebook in order using Google Colab or Jupyter Notebook.

### Steps:

1. **`luna16_candidates.ipynb`**  
   - Extracts candidate regions from raw CT scan data.  
   - Splits candidates into training, validation, and test sets.  
   - Applies data augmentation and saves the paths in `.csv` files.

2. **`luna16_model.ipynb`**  
   - Reads the prepared `.csv` files.  
   - Trains the deep learning model and performs evaluation.

3. **`luna16_visualization.ipynb`**  
   - Visualizes CT scans, predictions, and augmentation results.
