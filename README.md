# Online Retail Customer Segmentation

![Project Category](https://img.shields.io/badge/Project%20Category-Clustering-blue) ![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Enabled-brightgreen)

**Tools & Technologies Used**:  
![Python](https://img.shields.io/badge/Python-3.9-blue) ![NumPy](https://img.shields.io/badge/NumPy-Enabled-orange) ![Pandas](https://img.shields.io/badge/Pandas-Enabled-yellowgreen) ![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-red) ![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Visualization-yellow) ![Jupyter Notebooks](https://img.shields.io/badge/Jupyter-Notebook-blue) ![scikit-learn](https://img.shields.io/badge/scikit--learn-Machine%20Learning-green)

### Overview

This project focuses on analyzing data from a UK-based online retail company that sells unique gifts. The aim is to segment customers into distinct groups based on their purchasing behavior. By leveraging clustering algorithms and RFM analysis, we can better understand customer behavior and optimize marketing strategies to improve sales and customer satisfaction.

![Customer Clusters](https://drive.google.com/uc?export=view&id=1AKPMsInteturJu3dGxs-krTpXTdgBvqZ)

---

### Problem Statement

The task involves analyzing transactional data from a UK-based online retail company specializing in unique gifts. We aim to segment customers into groups based on their transactional behavior, improving customer targeting and enhancing overall marketing efforts.

---

### Data Description

- **Data Source**: [Dataset](https://docs.google.com/spreadsheets/d/1CAadjCrCzqgLQSGXDkrlkfViGvEKNPdU/edit?usp=drive_link&ouid=116881307272570964336&rtpof=true&sd=true)

We've gathered data about transactions from an online store based in the UK. Picture it like peeking into a world of shopping where each transaction tells a story. We know details like the unique transaction number, the products bought (each with its own name and code), how many of each product was purchased, when the purchase happened, the price of each product, and even where the customers live. It's like diving into a treasure trove of shopping adventures!

---

### Preliminary Questions

1. **Customer Behavior Understanding**:
    - What are the typical purchasing patterns of customers?
    - How frequently do customers make purchases within the given timeframe?
    - What is the distribution of purchase amounts across customers?
2. **Segmentation Potential**:
    - Can we identify distinct groups of customers based on their purchasing behavior?
    - Are there any trends or clusters in the data that suggest different customer segments?
3. **High-Value Customer Identification**:
    - Which customers have the highest recency, frequency, and monetary value (RFM) scores?
    - How do these high-value customers differ from the rest in terms of their purchasing behavior?

---

### Methodology

- **Data Cleaning**: Handled missing values, removed duplicates, and addressed anomalies in the dataset.
  
- **Feature Engineering**: Derived new features like RFM scores to capture customer behavior.

- **Data Visualization**: Used charts to identify trends and patterns in customer purchasing.

- **RFM Segmentation**: Grouped customers based on Recency, Frequency, and Monetary value.
  ![RFM](https://drive.google.com/uc?export=view&id=1mahuLJMXi9hl9Xfpa2Mde1-1VoEY6iNj)

- **Clustering Models**: Applied K-means and hierarchical clustering algorithms.

- **Evaluation Metrics**: Used Silhouette score and elbow method to optimize clustering results.

---

### Results & Insights

1. **Customer Segments**: Identified major customer segments such as Loyal Customers, Casual Buyers, and New Customers.
    ![Clusters](https://drive.google.com/uc?export=view&id=12dVo4jbXTYjkl7xRvoFnSobkG8XR8uWl)

2. **Popular Products**: Discovered top-selling products and slow-moving inventory.
    ![Customer Segments](https://drive.google.com/uc?export=view&id=1-LgcHk-SxRRh88cGtS4nXpnVrgvOMc1J)

3. **Geographic Insights**: Analyzed customer location data for targeted marketing.
    ![RFM Analysis](https://drive.google.com/uc?export=view&id=1KMigoRXSqeBLmGE620vVJU2UmnKFZmq6)

4. **Seasonal Trends**: Identified peak shopping seasons, such as Christmas.
    ![Seasonal Shopping](https://drive.google.com/uc?export=view&id=1wwdz3zCkRa0IHF3hoUu1zZN9kkpj2ePS)

---

### Model Comparison

| Clustering Method        | Optimal Clusters | Description                                                |
|--------------------------|------------------|------------------------------------------------------------|
| **K-Means**               | 3                | Segments: Loyal, Casual, and New Customers                  |
| **Hierarchical Clustering** | 2-3              | Dendrograms suggest 2 or 3 clusters depending on cut depth  |

---

### Impact and Implications

- **Targeted Marketing**: Tailored ads for specific customer groups.
- **Customer Relationship**: Enhanced relationships with personalized offers.
- **Product Development**: Data-driven decisions for product enhancement.
- **Cost Efficiency**: Focused on high-value customers to maximize ROI.

---

### Challenges & Limitations

1. **Data Quality**: Missing and duplicate data required careful handling.
2. **Behavior Complexity**: Differentiating customer behaviors can be complex.
3. **Privacy Concerns**: Ensuring data privacy and ethical use of customer information.
4. **Generalization**: Segmentations might not apply universally.

---

### Future Scope

1. **Refined Segmentation**: Use advanced algorithms for even more accurate segments.
2. **Predictive Analytics**: Predict future customer behavior for proactive strategies.
3. **Omnichannel Analysis**: Analyze customer behavior across online, store, and mobile.

---

### Conclusion

This project successfully segmented customers into actionable clusters using clustering techniques and RFM analysis, helping to improve marketing efforts and customer engagement.

---

### References

1. [Kaggle - Online Retail Customer Segmentation Analysis](https://www.kaggle.com/code/lakshmi25npathi/online-retail-customer-segmentation-analysis)
2. [Towards Data Science - Customer Segmentation in Online Retail](https://towardsdatascience.com/customer-segmentation-in-online-retail-1fc707a6f9e6)
3. (https://blog.converted.in/en-us/blog/a-detailed-guide-on-customer-segmentation-in-retail-e-commerce-business)

---

### Resources

- **Notebook**: [Google Colab Notebook](https://colab.research.google.com/drive/1wpHy0vwIxP5BZhgMgsZiBqPLEV1XS08U?usp=sharing)
- **GitHub**: [Online Retail Customer Segmentation](https://github.com/Rudrajit12/Online-Retail-Customer-Segmentation)

---

### About the Author

**Author**: Rudrajit Bhattacharyya  
This project was developed as part of the **AlmaBetter Full Stack Data Science** program.
  
- **Email**: [rudrajitb24@gmail.com](mailto:rudrajitb24@gmail.com)  
- **LinkedIn**: [rudrajitb](https://www.linkedin.com/in/rudrajitb/)  
- **GitHub**: [Rudrajit12](https://github.com/Rudrajit12)

---
