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
# Key Insights from Global Terrorism Analysis
# 1. Rising Trend of Attacks Over Time
Terrorist incidents have increased significantly over the years, with a sharp spike after 2010, indicating growing global instability and evolving threats.
# 2. High Concentration in Specific Regions
Terrorism is not evenly distributed. The Middle East & South Asia regions show the highest number of attacks and casualties, making them critical focus areas.
# 3. Most Affected Countries
Countries like Iraq, Afghanistan, and Pakistan experience the highest number of attacks and deaths, highlighting regional conflict zones.
# 4. Civilian Targets are Most Impacted
The majority of attacks target private citizens and property, followed by security forces, showing that civilians are the most vulnerable group.
# 5. Dominance of Certain Attack Types
Bombings and armed assaults are the most commonly used attack methods, indicating preferred tactics by terrorist groups.
# 6. Casualties Show High Impact Periods
Total deaths peaked around 2014–2015, showing periods of intense terrorist activity.
# 7. Known Groups Cause More Damage
Attacks claimed by known terrorist organizations tend to result in higher casualties compared to unclaimed or unknown group attacks.
# 8. Major Cities as Hotspots
Cities like Baghdad show extremely high incident counts, making them major hotspots for terrorist activity.
# 9. Limited Groups, Large Impact
A small number of terrorist organizations are responsible for a large share of incidents, indicating concentrated sources of threat.
# 10. High Success Rate of Attacks
A large number of attacks are marked as successful, which raises concerns about gaps in prevention and security measures.

# 📌 Final Insight
“Terrorism is highly concentrated, increasing over time, and driven by a limited number of groups using consistent attack patterns—highlighting the need for targeted, data-driven security strategies.”
  

