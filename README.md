## Findings from Exploratory Data Analysis

### 1. Statistical Insights
- A **T-Test** revealed that the number of words in the transcript is significantly different for selected and rejected candidates.

### 2. Similarity Analysis with TF-IDF
- Using **TF-IDF Vectorizer**, it was observed that:
  - The similarity between **Transcript** and **Job Description** is higher for selected candidates.
  - The similarity between **Transcript and Resume** and **Resume and Job Description** is comparatively lower.

### 3. Similarity Analysis with Word2Vec
- Using **Word2Vec**, the following patterns emerged:
  - The similarity between **Resume and Job Description**, **Job Description and Transcript**, and **Transcript and Resume** is higher for selected candidates compared to rejected candidates.

### 4. Role-Based Data Filtering
- Roles with sufficient data for training include:
  - **Data Analyst**, **Data Engineer**, **Data Scientist**, **Product Manager**, **Software Engineer**, **UI Designer**, and **UI Engineer**.
- Roles with limited data points (10–60) were excluded from the analysis.
