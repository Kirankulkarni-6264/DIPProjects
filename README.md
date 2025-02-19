# 🖼️ Image Manipulation in Google Colab

## 📌 Project Summary
This project showcases two key **image manipulation techniques** using **Google Colab**:
1. **Image Bit Depth Reduction**: Decreases the number of bits used to represent each pixel in a grayscale image.
2. **Spatial Downsampling**: Lowers the image's resolution by averaging neighboring pixel values.

Users can **upload a local image**, process it using either technique, and visually compare the output with the original.

---

## ⚙️ Requirements & Setup
No additional installations are needed!  
Google Colab has all required libraries pre-installed:
- `OpenCV` (`cv2`) – for image input/output and manipulation.
- `NumPy` – for array-based computations.
- `Matplotlib` – for image display.
- `Google Colab files` – for managing file uploads.

---

## 🚀 Running the Code in Google Colab
### **Step 1: Access Google Colab**
Navigate to [Google Colab](https://colab.research.google.com/) and create a new notebook.

### **Step 2: Integrate the Code**
Paste the **Python script** (`DigitalImageProcessing.ipynb`) into a Colab cell.

### **Step 3: Execute the Script**
Click **"Run"** or use `Shift + Enter`.  
A **file selection window** will appear.

### **Step 4: Upload an Image**
- Select **"Choose Files"** and upload a **grayscale image** (`.png`, `.jpg`, `.bmp`, etc.).
- The script will automatically process the image upon upload.

### **Step 5: Select a Process**
- Type `1` for **Image Bit Depth Reduction**.
- Type `2` for **Spatial Downsampling**.

### **Step 6: Examine the Results**
The processed image will be **displayed** alongside the original for comparison.

---

## 🛠️ Features & Testing
✔️ **Supports grayscale images** (PNG, JPG, BMP, TIFF formats).  
✔️ **Bit Depth Control:** Choose from `1-8` bit levels.  
✔️ **Resolution Reduction:** Select a **downsampling factor (2, 4, 8, etc.)**.  
✔️ **Interactive Upload and Processing within Google Colab**.  
✔️ **Automatic file path handling**.  

### **Tested On:**
- **Google Colab**
- **Python 3.9+**
- **OpenCV 4+**

---

## ⚠️ Important Considerations
- Only **grayscale images** are currently supported.
- If the file upload malfunctions, try restarting the Colab runtime (`Runtime > Restart and run all`).
- **Reducing bit depth** decreases **image detail**.
- **Higher downsampling factors** can introduce **blurriness**.
