# 🌲 Tree Species Classification using 3D Point Clouds & Multi-view Approaches

## 🧩 Project Overview
This project focuses on **implementing and comparing different methods** for **tree species classification** using 3D point cloud data and multi-view image techniques.  
The objective is to evaluate the performance of several classification pipelines to identify which approach performs best.

---

## 📦 Dataset

- **Source:** [Dataset on Göttingen Research Online](https://data.goettingen-research-online.de/dataset.xhtml?persistentId=doi:10.25625/FOHUJM)  
- **Description:** Contains 3D point clouds of trees belonging to 7 species.  
- **Total samples:** 691 trees.

| Species        | Count |
|----------------|--------|
| Beech          | 164    |
| Red Oak        | 100    |
| Ash            | 39     |
| Oak            | 22     |
| Douglas Fir    | 183    |
| Spruce         | 158    |
| Pine           | 25     |
| **Total**      | **691** |

---

## 🧠 Classification Methods

### 1️⃣ Indirect (2D Multi-view Approaches)
- Multi-view + Classical Descriptors + Classical ML Model  
- Multi-view + CNN (trained from scratch)  
- Multi-view + Pretrained CNN (Fine-tuning & Transfer Learning)  
- Multi-view + Pretrained CNN + Classical ML Model  
- Multi-view + Descriptors + CNN (Data Fusion)

### 2️⃣ Quasi-direct Methods
- Apply **3D descriptors** directly on point clouds  
- Use **classical ML algorithms** for classification

### 3️⃣ Direct Methods
- Deep learning directly on 3D point clouds  
  - **PointNet** → [Implementation](https://github.com/charlesq34/pointnet)  
  - **DGCNN** → [Implementation](https://github.com/WangYueFt/dgcnn)

---

## 🧰 Tools & Libraries
- Python (NumPy, Pandas, Matplotlib)
- Open3D (3D visualization)
- PyTorch / torchvision
- scikit-learn
- Jupyter Notebook

---

## 📊 Results
| Method | Accuracy | Comments |
|---------|-----------|----------|
| Multi-view CNN (scratch) | xx% | Basic CNN trained on 2D views |
| Pretrained CNN (transfer learning) | xx% | Best balance between performance and training time |
| PointNet | xx% | Works directly on point clouds |
| DGCNN | xx% | Achieved the highest overall accuracy |

*(Replace xx% with your actual results.)*

---

## 📄 Project Report
You can read the full project report here:  
📘 [Download the PDF](./VFTree_Classification_Report_ArehalBtissam_ElfaizRekaia_ErreghayHajar.pdf)

---



---

## 🧾 License
This project is part of an academic work.  
Please cite this repository if you reuse or extend it.

---

### ⭐ If you find this project useful, don’t forget to give it a star on GitHub!
