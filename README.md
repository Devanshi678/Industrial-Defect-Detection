# Industrial-Defect-Detection
# Solar Cell Defect Detection using YOLOv8  
End-to-end computer vision pipeline for detecting defects in electroluminescence (EL) solar cell images.

This project uses the **ELPV dataset** (Electroluminescence Photovoltaic Dataset) and builds a full workflow including:
- Dataset preparation & YOLO formatting  
- EDA & preprocessing  
- YOLOv8 training  
- Evaluation & visualization  
- Streamlit deployment (image upload + webcam)  
- SQL logging  
- PowerBI/Tableau dashboard  
- Model card & documentation  

---

# 📦 Dataset  
**Name:** ELPV Dataset  
**Source:** https://github.com/zae-bayern/elpv-dataset  
**License:** **CC BY-NC-SA 4.0** (Non-Commercial)  
**Description:**  
- 2,624 images (300×300 px, 8-bit grayscale)  
- Solar cell EL images labeled as *functional* or *defective*  
- Varying defect severity, from intrinsic + extrinsic degradation  
- Perspective & lens-distortion corrected  

⚠️ **Important**:  
The dataset is licensed under **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.  
This means:  
- ✔ You **may use** the data for research, education, personal projects  
- ❌ You **may NOT use** the data commercially  
- ✔ You must **credit the authors**  
- ✔ Derivative datasets must be licensed under the **same terms (ShareAlike)**  

For commercial usage, contact the original authors (as requested in the dataset README).

---

# 🧩 Project Structure  
