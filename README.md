# Image Enhancement with CLAHE in Google Colab

This project demonstrates how to apply **Contrast Limited Adaptive Histogram Equalization (CLAHE)** to improve the contrast of grayscale images. It includes a Google Colab notebook with practical examples and parameter tuning for `clipLimit` and `tileGridSize`.

## 📂 Project Structure
- `notebook.ipynb`: Google Colab notebook with the full implementation.
- `data/`: Folder containing sample grayscale images.

## 🚀 How to Use in Google Colab
1. Open the notebook in Colab:
   https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO/blob/main/notebook.ipynb

2. Clone the repository inside Colab:
```python
!git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
%cd YOUR_REPO
```

3. Run the cells to:
- Load images from data/.
- Apply CLAHE.
- Visualize before/after results.

## ⚙️ Parameter Tuning
- clipLimit: Controls the contrast limit (typical values: 2.0 to 4.0).
- tileGridSize: Defines the grid size for local histogram equalization (e.g., (8,8) or (16,16)).

## ✅ Requirements
Google Colab (includes OpenCV and Matplotlib by default).
Internet connection to clone the repository.

## 📦 Download or Backup Data
To download the data folder from Colab:
```python
!zip -r data.zip data
from google.colab import files
files.download("data.zip")
```

## 📜 License
This project is distributed under the MIT License.
