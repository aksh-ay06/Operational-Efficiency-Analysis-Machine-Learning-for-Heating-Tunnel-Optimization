# **Energy Analytics in Action: Heating Tunnel Project**

This repository contains the implementation of the *Heating Tunnel Project*, a comprehensive application of unsupervised machine learning techniques for industrial process optimization. The project identifies operational inefficiencies and potential sources of quality defects in a manufacturing heating tunnel system using clustering analysis.

## **Project Overview**

The goal of this project was to analyze operational energy data from a heating tunnel system, detect patterns, and uncover anomalies leading to quality defects and increased energy consumption. Using the CRISP-DM methodology, the project encompasses all phases from business understanding to deployment.

### **Key Objectives**
- Analyze archived operational data to identify inefficiencies in energy consumption.
- Implement unsupervised clustering algorithms to group operational patterns.
- Draw actionable insights for improving manufacturing consistency and efficiency.

---

## **Features**
- **Data Preprocessing**: Data cleaning, standardization, and preparation for analysis.
- **Machine Learning**: Implementation of the Time Series KMeans algorithm for clustering.
- **Evaluation Metrics**: Use of Silhouette and Calinski-Harabasz scores for cluster validation.
- **Visualization**: Graphical representation of energy consumption patterns and clustering results.

---

## **Technologies Used**
- **Programming Language**: Python
- **Libraries**:
  - `tslearn` for time series clustering
  - `numpy` and `pandas` for data manipulation
  - `matplotlib` for data visualization
  - `scikit-learn` for evaluation metrics
- **Tools**: Jupyter Notebook / Google Colab

---

## **Project Structure**
```
Heating_Tunnel_Project/
│
├── data/                       # Raw and processed data files
├── notebooks/                  # Jupyter notebooks for each phase of the project
│   ├── Phase_1_Business_Understanding.ipynb
│   ├── Phase_2_Data_Understanding.ipynb
│   ├── Phase_3_Data_Preprocessing.ipynb
│   ├── Phase_4_Model_Implementation.ipynb
│   └── Phase_5_Evaluation_and_Deployment.ipynb
├── outputs/                    # Visualizations and clustering results
├── requirements.txt            # Required Python libraries
└── README.md                   # Project documentation
```

---

## **How to Use**
1. Clone this repository:
   ```bash
   git clone https://github.com/aksh-ay06/Operational-Efficiency-Analysis-Machine-Learning-for-Heating-Tunnel-Optimization.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Operational-Efficiency-Analysis-Machine-Learning-for-Heating-Tunnel-Optimization
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open the Jupyter Notebooks in the directory to follow each project phase:
   ```bash
   jupyter Project_3(Smart_manufacturing).ipynb
   ```

---

## **Results**
The project successfully identified two distinct operational patterns and highlighted inefficiencies related to:
- Operator-dependent parameter variations.
- Maintenance inconsistencies in pneumatic systems.
- Process control limitations due to the absence of automation.

### **Cluster Analysis Metrics**
- **Silhouette Score**: 0.65–0.66
- **Calinski-Harabasz Score**: 63.03–82.04

---

## **Contributors**
- **[Akshay Patel]**  
  Graduate Student in Industrial Engineering  
  Email: [akshaypatelnitb6@gmail.com]  
