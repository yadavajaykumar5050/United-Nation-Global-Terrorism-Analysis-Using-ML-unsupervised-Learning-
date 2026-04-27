# United-Nation-Global-Terrorism-Analysis-Using-ML-unsupervised-Learning-and-PowerBI

![image alt](https://github.com/yadavajaykumar5050/United-Nation-Global-Terrorism-Analysis-Using-ML-unsupervised-Learning-/blob/main/Machine-Learning-Workflow-1024x683.webp?raw=true)

# 📌 Project Overview
This project presents a comprehensive analysis of global terrorism incidents using unsupervised machine learning and interactive Power BI dashboards. The objective is to discover hidden patterns in terrorism incidents and classify them into severity-based clusters using casualty-related features such as number of people killed and wounded. The project combines data preprocessing, exploratory data analysis, clustering models, evaluation metrics, and dashboard visualization to support data-driven decision making.

# **Objective**
* To detect geographical terrorism hotspots without predefined cluster count.
* This means we want to identify high-risk regions automatically from the data, without telling the model how many clusters (hotspots) to form.

# 🤖 Machine Learning Approach
Unsupervised learning algorithms were applied to identify hidden severity patterns.
# K-Means Clustering 
# **Insights:**
* Data grouped into clusters based on similarity
* Some clusters show high activity regions
* Requires predefined K
* Cannot detect irregular shapes

#  **2) PCA(Dimensionality Reduction)**
# **Insights:**
* Data reduced to 2 components
* Helps visualize patterns clearly
* Shows separation between clusters
* Not used for clustering directly

# **3) DBSCAN**(Best Performance)
* No need for cluster count
* Detects dense regions
* Handles noise
* Works best for geographical data

  # **Final Insights**
* Terrorism incidents are not random
* They are concentrated in specific hotspots
* Some areas consistently show high activity
* There are rare isolated attacks (outliers)
* Patterns are irregular and complex

  # **Conclusion**
* Unsupervised learning helps uncover hidden patterns in terrorism data
* K-Means and PCA provide basic understanding
* DBSCAN effectively detects real-world hotspots
* It is the best algorithm for this objective
* The results can help in security planning and risk management


# Power Bi Dashboard

![image alt](https://github.com/yadavajaykumar5050/United-Nation-Global-Terrorism-Analysis-Using-ML-unsupervised-Learning-/blob/main/Power%20BI%20Dashboard.png?raw=true)



  

