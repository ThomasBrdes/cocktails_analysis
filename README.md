# 🍸 Cocktails Data Analysis

This project provides a comprehensive analysis of cocktail ingredients and their frequencies across various recipes. The aim is to uncover patterns, most frequent ingredients, and clustering trends in the cocktail world! 🥂

## ✨ Features

- 🍋 Ingredient Analysis: Explore the most common ingredients across a wide variety of cocktail recipes.
- 📈 Visualizations: Generate detailed visualizations of ingredient distributions.
- 🍹 Clustering: Group cocktails based on ingredient similarity and discover interesting trends.

## 📊 Results

The analysis reveals the most frequent cocktail ingredients and provides insights into their distributions. Check the [Cocktails_analysis.pdf](Cocktails_analysis.pdf) report or explore the results interactively in the notebooks.

## 📁 Project Structure
```bash
    ├── imgs # 📊 Generated images and plots 
    ├── src # 🧠 Source code for data analysis 
    ├── Cocktails_analysis.pdf # 📄 PDF report summarizing the analysis 
    ├── cocktails_data_analysis.ipynb # 📝 Main analysis notebook 
    ├── cocktails_data_analysis_annexes.ipynb # 📚 Supplementary notebook 
    ├── environment.yml # ⚙️ Conda environment configuration 
    └── README.md # 📖
 ```

## 🛠️ Requirements

- Python 3.x 🐍
- Jupyter Notebook 📒
- Conda (for environment management) ⚙️


## 🚀 Quick Start

Follow these instructions to get the project up and running on your local machine.

### 1. Clone the repository:

```bash
git clone https://github.com/ThomasBrdes/cocktails_analysis.git
cd cocktails_analysis
```

### 2. Install env:

```bash
conda env create -f environment.yml
conda activate cocktails_analysis
```

### 3. Launch Jupyter:

```bash
jupyter notebook
```

## 💻 Tech Stack

- **Python**: Programming language
- **Dataviz**: matplotlib, pandas, seaborn
- **ML-models**: supervised models (Logistic regression, Quadratic logistic regression) and un-supervised models (K-means, KPPV)


## 📚 Acknowledgements

🔍 **Data from** : [Cocktails_data_link](https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-05-26/readme.md)
