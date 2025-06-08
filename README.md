# Fake-News-Detection: 

# 📊 Fake News Detection – Data Visualization

Welcome to the **Fake News Detection Data Visualization** project!  
This project focuses on exploring and visualizing the dataset used to classify news as **real or fake**, helping uncover key patterns and trends in the data.

---

## 📁 Dataset

**🔗 Dataset File:**  
[Click to view Dataset.main](https://github.com/vanshikaaaaa12/Fake-News-Detection/blob/main/review2/Dataset.main)

The dataset contains news articles labeled as either fake or real. Key columns include:

- `title` – Headline of the article  
- `text` – Full text content  
- `subject` – Topic or category of the article  
- `label` – Binary label (1 = Fake, 0 = Real)

---

## 🎯 Visualization Objectives

The main goal of the visualization is to **understand the characteristics of fake and real news** by analyzing various textual and categorical features. Specifically, we aim to:

1. Visualize the **distribution of fake vs real news**
2. Analyze **common topics** (subjects) in both categories
3. Identify differences in **text length**, **title length**, and **word usage**
4. Highlight patterns using **interactive visualizations**
5. Support future model-building through **insightful feature understanding**

---

## 📊 Visualizations Overview

The following types of visualizations are included:

| Visualization Type     | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| Bar Charts             | Compare count of fake and real articles, and distribution by subject        |
| Pie Charts             | Show proportion of subject categories                                       |
| Word Clouds            | Highlight most frequent words in fake vs real articles                      |
| Histograms             | Analyze text length and title length                                        |
| Scatter Plots          | Explore relationships between text metrics and fake/real labels             |
| Interactive Charts     | Zoom, hover, and explore deeper insights using Plotly charts                |

---

## 🧩 Interactivity

Some visualizations use **Plotly** for enhanced interactivity:

- 🖱️ **Hover over data points** to view tooltips with extra context
- 🔍 **Zoom and pan** to explore data clusters or dense regions
- 📊 **Toggle series** using legends in grouped visualizations

---

## 🧑‍💻 How to Run the Code

**🔗 Visualization Source Code:**  
[Click to view Data Visualization.main](https://github.com/vanshikaaaaa12/Fake-News-Detection/blob/main/review2/Data%20Visualization.main)

### 🔧 Requirements

Make sure you have the following Python packages installed:

```bash
pip install pandas matplotlib seaborn plotly wordcloud nltk

🚀 Steps
Clone the repository:

bash
Copy
Edit
git clone https://github.com/vanshikaaaaa12/Fake-News-Detection.git
cd Fake-News-Detection/review2
Open the Data Visualization.main file in Jupyter Notebook or any Python IDE.

Run each cell step-by-step to see the visualizations and insights.

📝 Storytelling with Visuals
Each chart is annotated or described to help explain what the data is showing.
Examples:

Bar chart comparing survival by class includes a note highlighting the higher survival in 1st class

Word clouds compare linguistic patterns in fake vs real news

Text length histograms suggest fake news articles may use longer, more emotional content

These narratives guide the user through the "what" and the "why" behind the data.

🧠 Insights Uncovered
Certain subjects are more associated with fake news

Fake news articles often have longer or emotionally charged headlines

Real news tends to stick with factual and concise wording

These findings can inform feature engineering for fake news classifiers.


