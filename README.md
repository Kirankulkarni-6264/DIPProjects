# 🖼️ Image Quantization & Resolution Reduction in Google Colab

## 📌 Project Overview
This project demonstrates two fundamental **image processing operations** using **Google Colab**:
1. **Image Quantization**: Reduces the bit depth of a grayscale image.
2. **Spatial Resolution Modification**: Reduces the spatial resolution of an image by averaging neighboring pixels.

The script allows users to **upload an image from their local system**, process it, and visualize the results.

---

## ⚙️ Dependencies & Setup
No external installations are required!  
Google Colab comes pre-installed with all necessary libraries:
- `OpenCV` (`cv2`) – for image loading and processing.
- `NumPy` – for numerical computations.
- `Matplotlib` – for visualizing images.
- `Google Colab files` – for handling file uploads.

---

## 🚀 Running the Code in Google Colab
### **Step 1: Open Google Colab**
Go to [Google Colab](https://colab.research.google.com/) and create a new notebook.

### **Step 2: Copy & Paste the Code**
Copy the **Python script** (`DigitalImageProcessing.ipynb`) into a Colab cell.

### **Step 3: Run the Script**
Click **"Run"** or press `Shift + Enter`.  
A **file selection dialog** will appear.

### **Step 4: Upload an Image**
- Click **"Choose Files"** and upload a **grayscale image** (`.png`, `.jpg`, `.bmp`, etc.).
- The script will automatically process the image.

### **Step 5: Choose an Operation**
- Enter `1` for **Image Quantization** (bit depth reduction).
- Enter `2` for **Resolution Reduction** (downsampling).

### **Step 6: View and Analyze the Results**
The processed image will be **displayed** next to the original.

---

## 🛠️ Features & Testing
✔️ **Supports grayscale images** (PNG, JPG, BMP, TIFF).  
✔️ **Bit Depth Reduction:** Choose from `1-8` bit levels.  
✔️ **Resolution Downsampling:** Choose **factor (2, 4, 8, etc.)**.  
✔️ **Interactive File Upload & Processing in Google Colab**.  
✔️ **No manual path entry required**.  

### **Tested On:**
- **Google Colab**
- **Python 3.9+**
- **OpenCV 4+**

---

## ⚠️ Notes & Edge Cases
- Ensure that the **uploaded image is grayscale**.
- If the file upload fails, restart the Colab runtime (`Runtime > Restart and run all`).
- **Lower bit depth** results in **loss of detail**.
- **Higher resolution reduction factors** can cause **blurring**.


