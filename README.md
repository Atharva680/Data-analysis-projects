# Data-analysis-projects
# 📊 GitHub Repository File Analysis  
*Analyzing Open Source Trends from File-Level GitHub Data*

---

## 🧠 Project Overview

This project focuses on analyzing the **structure, language usage, and file content trends** in open-source GitHub repositories using a custom dataset with the following format:

- `sample_path` – The relative file path in the repository
- `content` – The source code or text content of the file
- `extension` – The file extension representing the language (e.g., `py`, `js`, `html`)

By analyzing these features, we gain insights into:
- Popular technologies and languages
- Common code patterns and keywords
- Directory structures and modularity practices

---

## 🎯 Research Objectives

1. **Understand technology trends** by analyzing file extensions across repositories.
2. **Quantify code composition** by measuring lines, keywords, and file structures.
3. **Visualize directory depth and modularization** in modern repositories.
4. **Compare usage of languages like Python, JavaScript, C++** using word frequency, file types, and layout.

---

## 📁 Dataset Format

| Column Name   | Description |
|---------------|-------------|
| `sample_path` | Path of the file inside a GitHub repo (e.g., `src/App.js`) |
| `content`     | Raw source code or text content of the file |
| `extension`   | File type/extension (e.g., `py`, `js`, `html`) |

> 📌 Dataset collected via GitHub API, file crawlers, or open datasets (e.g., CodeSearchNet, BigCode).

---

## 📊 Key Visualizations

- **Bar Plot** – Top file extensions by count
- **Word Cloud** – Most common keywords in Python or JavaScript files
- **Histogram** – File path depth distribution
- **Heatmap** – Keyword frequency by file type
- **Stacked Area Chart** – File extension usage over time (if timestamp available)

---

## 🔧 Tools & Libraries Used

| Tool            | Purpose                     |
|-----------------|-----------------------------|
| `Python`        | Main programming language   |
| `Pandas`        | Data manipulation           |
| `Matplotlib`    | Basic visualizations        |
| `Seaborn`       | Statistical plots           |
| `WordCloud`     | Text frequency visualization|
| `PyGitHub`      | GitHub data extraction (optional) |

---

## 📌 Installation

```bash
git clone https://github.com/<your-username>/github-file-analysis.git
cd github-file-analysis
pip install -r requirements.txt



@project{github_file_analysis_2025,
  title={Analyzing GitHub Repositories at File Level: Tech Stack Trends, Structures, and Content},
  author={Atharva Shinde},
  year={2025},
  howpublished={GitHub},
  note={\url{https://github.com/<your-username>/github-file-analysis}}
}
