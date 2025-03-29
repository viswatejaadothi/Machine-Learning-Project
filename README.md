
# 🧠 Customer Segmentation Using Clustering Techniques

This project applies unsupervised machine learning techniques to perform **customer segmentation** based on demographic and behavioral data using the **Mall Customers Dataset**. The primary goal is to identify meaningful customer groups to support targeted marketing strategies, customer engagement, and business decision-making.

---

## 👥 Group Members

| Student ID   | Name                  |
|--------------|-----------------------|
| T00728369    | Huynh Hiep Tran (Alex)|
| T00736529    | Viswateja Adothi      |
| T00736533    | Akansha Bhargavi      |
| T00729053    | Khadiza Tannee        |

---

## 📁 Project Structure

```bash
├── ADSC_4710_Machine_Learning_Final_Report.pdf   # Final project report
├── Mall_Customers.csv                             # Dataset
├── hierarchical_clustering.ipynb                  # Hierarchical Clustering + behavioral analysis
├── kmeans_clustering.ipynb                        # K-Means Clustering
├── clustering_summary_comparison.ipynb            # Summary and model comparison
├── venv/                                          # (Optional) Python environment folder
```

---

## 🚀 How to Run (Google Colab Recommended)

> 🟢 This project is intended to be run in **Google Colab** for best compatibility and ease of setup.

### 🔄 Order of Execution:

1. **Run `hierarchical_clustering.ipynb` first**  
   - This notebook includes full preprocessing, linkage method testing, dendrogram visualization, and PCA.
   - At the end, it includes a new section:  
     ✅ **Income vs. Spending Score Analysis by Age Group** — adds deeper behavioral insights through derived features.

2. **Run `kmeans_clustering.ipynb` next**  
   - Applies K-Means clustering with Elbow Method and PCA visualization.
   - Compares cluster quality using Silhouette Score.

3. **Run `clustering_summary_comparison.ipynb`**  
   - Summarizes and compares results between the two clustering methods.

---

## 📝 Output

- **Final report** is available in `.pdf` format (`ADSC_4710_Machine_Learning_Final_Report.pdf`)
- Each notebook is annotated with markdown cells for clarity and explanation.

---

## 📦 Dependencies

Google Colab includes all required libraries. If running locally, install:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

---

## 📬 Contact

For questions or feedback, feel free to reach out to any of the group members listed above.
