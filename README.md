# 🛣️ Road Expansion and Tree Loss Monitoring using Deep Learning

This project analyzes satellite imagery to detect areas affected by road expansion and quantify the resulting loss in tree cover using object detection and segmentation models. It supports environmental monitoring, impact assessment, and deforestation analysis through spatial-temporal comparisons.

---

## 📌 Project Summary

Using deep learning models (YOLOv8, U-Net, Faster R-CNN) and QGIS-based geospatial analysis, we detect roads and trees before and after infrastructure expansion to assess vegetation impact.

---

## 🎯 Objectives

- Detect road expansion zones using satellite images.
- Identify and count trees lost due to road development.
- Generate visual and geospatial reports on tree loss.
- Assist decision-makers with actionable environmental insights.

---

## 🧰 Technologies & Tools

- **Languages**: Python  
- **Libraries**: TensorFlow, PyTorch, OpenCV, NumPy, Pandas  
- **Models**: YOLOv8, U-Net, Faster R-CNN  
- **Annotation**: Roboflow, LabelImg  
- **GIS Tools**: QGIS, Shapefiles  
- **Environment**: Google Colab  

---

## 🔁 Workflow Overview

1. **Satellite Image Collection**: Before-and-after road expansion images.
2. **Annotation**: Trees and roads annotated using Roboflow.
3. **Model Training**:
   - YOLOv8 and Faster R-CNN for object detection.
   - U-Net for segmentation of tree canopies.
4. **Spatial Analysis**:
   - Detected trees compared across time.
   - Tree loss visualized in QGIS.
5. **Reporting**:
   - Spatial and quantitative analysis of tree loss.
   - Generated shapefiles and maps for reporting.

---

## 📊 Results

- Detected and visualized significant deforestation near newly constructed roads.
- Quantified tree loss using pixel-based comparison and bounding box detection.
- Generated GIS-compatible outputs for integration into planning workflows.

---

## 📈 Key Learnings

- Road expansion significantly impacts tree density in nearby regions.
- Combining segmentation and detection provides more precise monitoring.
- QGIS enhances understanding of AI results through spatial visualization.

---

## 🔒 Code Access Notice

To maintain data confidentiality and ensure project security, the source code for this project is currently private.  
📩 **For collaboration or code access, please contact the project owner.**

---

## 👤 Author

**Dhruti Patel**  
📧 dhrutiharhshadkumar@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/dhruti-p-)  
🐙 [GitHub](https://github.com/dhrutipatel18)

---

⭐ If you're interested in collaboration or research partnerships, feel free to connect!
