# Browntail Moth Infestation Analysis and Prediction

## A nine-hour data marathons

**By: Team Null (Baron Wang, Ziyan Zhang, Bishal Khadka, Yiheng Su)**

---

## 📖 Overview

The Browntail Moth (BTM) is an invasive species found along the coast of Maine and Cape Cod, causing forest and human health issues. This project focuses on understanding and predicting BTM infestations in Waterville using data analysis, machine learning, and visualization.

### Goals:

1. **Analyze the distribution of BTM infestations in Waterville.**
2. **Predict whether a tree will be infested and recommend treatments.**
3. **Identify factors contributing to BTM infestations.**
4. **Provide actionable recommendations to mitigate BTM spread.**

---

## 📊 Data and Methods

This project leverages:

- **BTM Infestation Data**: Includes tree characteristics, infestation patterns, and treatment records.
- **Geospatial Data**: Locations of trees with infestation observations.
- **Machine Learning Models**: Random Forest and k-means clustering for prediction and analysis.
- **Visualization Tools**: Scatter maps, density maps, and violin plots to explore data patterns.

### Key Analysis:

1. **Correlation Analysis**: Tree size (DBH) vs. infestation intensity.
2. **Clustering**: k-means clustering to group trees based on infestation proximity and water distance.
3. **Prediction Models**:
   - Infestation likelihood prediction.
   - Treatment type recommendation.

---

## 📂 Repository Structure

- **`BTM_Cluster.ipynb`**: Clustering analysis using k-means to identify infestation patterns.
- **`BTM_data_prepared.csv`**: Cleaned dataset used in modeling and visualization.
- **`BTM_Existence_Prediction.ipynb`**: Random Forest model predicting tree infestation.
- **`Treatment_Prediction.ipynb`**: Random Forest model predicting treatment type for trees.
- **`README.md`**: Project overview and instructions.
- **`Team Null Presentation.pdf`**: Final presentation summarizing methods, findings, and recommendations.

---

## 📦 Requirements

### Python Packages

Install dependencies using:

```bash
pip install -r requirements.txt
```

### Additional Tools

- **Dataiku**: For visualization and analysis.
- **Python Libraries**: NumPy, pandas, scikit-learn, matplotlib.

---

## 📈 Results

### **1. Distribution Patterns**

- Infested trees are concentrated near water sources.
- Larger trees (greater DBH) have a higher likelihood of infestation.

### **2. Prediction Models**

- **Infestation Prediction**: Achieved 91.2% accuracy. Key predictors include geolocation and tree type.
- **Treatment Recommendation**: Achieved perfect accuracy due to alignment with existing treatment algorithms.

### **3. Clustering Insights**

- Trees near rivers form distinct clusters of infestation, highlighting proximity to water as a key factor.

---

## 🌟 Policy Recommendations

1. **Targeted Control Campaigns**:

   - Focus insect control efforts along rivers and dense infestation areas.
2. **Improved Treatment Algorithms**:

   - Enhance decision-making for treatment assignment using predictive models.
3. **Public Advisories**:

   - Provide recommendations for residents with susceptible tree types.

---

## 🚀 Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/browntail-moth-analysis.git
   ```
2. Run Jupyter Notebooks for data exploration, analysis, and modeling.

---

## Key Takeaway

This project highlights the power of data-driven insights in understanding and mitigating environmental challenges. By combining machine learning, visualization, and actionable recommendations, we provide a roadmap to combat BTM infestations effectively.
