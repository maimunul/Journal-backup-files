# 🌾 **Rice Leaf Disease Classification using Resource-Efficient Deep Learning Models via Response-Based Knowledge Distillation**  

![Proposed Architecture](https://github.com/maimunul/Rice-Leaf-Disease-Classification-using-Resource-Efficient-Deep-Learning-Models-via-Response-Based/blob/main/analysisPic/Methodology%20fig/proposedarchitecture.png)  

---

## 📖 Introduction  

This project explores **resource-efficient deep learning** by leveraging **Response-Based Knowledge Distillation (KD)** to classify rice leaf diseases. The aim is to create lightweight yet accurate models suitable for **resource-constrained environments** like mobile or IoT devices.  

---

### What is Knowledge Distillation?  

Knowledge distillation involves training a smaller **student model** to replicate the performance of a larger **teacher model** by learning from its **predictions**.  

#### Categories of KD:  
1. **Response-Based KD**: Aligns teacher and student model outputs using metrics like Kullback-Leibler divergence.  
2. **Feature-Based KD**: Transfers intermediate representations from teacher to student.  
3. **Relation-Based KD**: Preserves pairwise relationships between data samples.  

For this project, **Response-Based KD** is used due to its simplicity and effectiveness in CNN models.  

---

## 🌾 Dataset  

The dataset used is the **Rice Leaf Disease Dataset** from [Mendeley Data](https://data.mendeley.com/datasets/fwcj7stb8r/2), containing **5,932 images** across four rice leaf diseases:  
- **Bacterial Blight**  
- **Blast**  
- **Brown Spot**  
- **Tungro**  

---

### 📊 Dataset Overview  

| **Disease Type**       | **Percentage (%)** | **Training Set** | **Validation Set** | **Test Set** |  
|-------------------------|---------------------|-------------------|---------------------|--------------|  
| Bacterial Blight        | 26.7%              | 1267             | 158                 | 159          |  
| Blast                   | 24.3%              | 1152             | 144                 | 144          |  
| Brown Spot              | 27.0%              | 1280             | 160                 | 160          |  
| Tungro                  | 22.0%              | 1046             | 130                 | 132          |  
| **Total**               | **100%**           | **4745**         | **592**             | **595**      |  

---

### 📷 Dataset Visualization  

Below are sample images from the dataset:  

| **Bacterial Blight**       | **Blast**             | **Brown Spot**         | **Tungro**            |  
|-----------------------------|-----------------------|-------------------------|-----------------------|  
| ![Bacterial Blight](https://github.com/maimunul/Rice-Leaf-Disease-Classification-using-Resource-Efficient-Deep-Learning-Models-via-Response-Based/blob/main/train/Bacterialblight/BACTERAILBLIGHT3_085.jpg) | ![Blast](https://github.com/maimunul/Rice-Leaf-Disease-Classification-using-Resource-Efficient-Deep-Learning-Models-via-Response-Based/blob/main/train/Blast/BLAST1_031.JPG) | ![Brown Spot](https://github.com/maimunul/Rice-Leaf-Disease-Classification-using-Resource-Efficient-Deep-Learning-Models-via-Response-Based/blob/main/train/Brownspot/BROWNSPOT1_009.jpg) | ![Tungro](https://github.com/maimunul/Rice-Leaf-Disease-Classification-using-Resource-Efficient-Deep-Learning-Models-via-Response-Based/blob/main/train/Tungro/TUNGRO1_002.jpg) |  

---

## 🚀 Response-Based Knowledge Distillation  

Response-Based KD enhances model efficiency by transferring **soft predictions** from a teacher model to a student model. The student uses these probabilistic outputs, alongside true labels, to generalize better.  

### Why KD?  
- **Efficiency**: Reduces model size for faster inference.  
- **Deployment**: Ideal for **edge devices**, **IoT**, and **mobile platforms**.  

---

## 📌 Key Features  
- **Lightweight Models**: Optimized for resource-constrained environments.  
- **High Accuracy**: Maintains predictive performance.  
- **Flexible Deployment**: Designed for mobile and IoT devices.  

---

## 📚 References  
- [Hinton et al. (2015)](https://arxiv.org/abs/1503.02531): Distilling the Knowledge in a Neural Network  

---

## ✨ Future Scope  
- Extend to other crop diseases.  
- Integrate additional knowledge distillation techniques.  

---


# Contributors

We would like to acknowledge the following contributors to this project:

| Contributor Name              | Affiliation                                                                                             | Photo                                                      |
|-------------------------------|---------------------------------------------------------------------------------------------------------|------------------------------------------------------------|
| **Maimunul Karim Jisan**       | Department of Computer Science and Engineering, East Delta University, Chittagong, Bangladesh          | <img src="https://github.com/maimunul/Rice-Leaf-Disease-Classification-using-Response-Based-Knowledge-Distillation/blob/main/ContributorPic/MaimunulKarimJisan.jpg" width="150" height="150" /> |
| **Kazi Ekramul Hoque**         | School of Information and Communication Technology, Griffith University, Brisbane, Australia [Google Scholar](https://scholar.google.com/citations?user=yk3Ql4YAAAAJ&hl=en) | <img src="https://github.com/maimunul/Rice-Leaf-Disease-Classification-using-Response-Based-Knowledge-Distillation/blob/main/ContributorPic/KaziEkramulHoque%20(1).JPG" width="150" height="150" /> |
| **Tanvir Azhar**               | Department of Computer Science and Engineering, East Delta University, Chittagong, Bangladesh          | <img src="https://github.com/maimunul/Rice-Leaf-Disease-Classification-using-Response-Based-Knowledge-Distillation/blob/main/ContributorPic/Tanvir_Azhar.jpg" width="150" height="150" /> |
| **M.A. Hakim Newton**          | School of Information and Physical Sciences, The University of Newcastle, Australia [Google Scholar](https://scholar.google.com/citations?user=GGxzBNYAAAAJ&hl=en)                    | <img src="https://github.com/maimunul/Rice-Leaf-Disease-Classification-using-Response-Based-Knowledge-Distillation/blob/main/ContributorPic/MA%20HakimNewton.jpg" width="150" height="150" /> |







  
