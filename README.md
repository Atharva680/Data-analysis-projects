# 📊 GitHub File-Level Analysis: Tech Stack Trends & Repository Metadata

This project presents an analytical overview of GitHub repositories at the **file level**, uncovering trends in tech stacks, file structures, and metadata like stars, contributors, and creation dates. It is intended for researchers, data analysts, and developers interested in understanding how codebases evolve and which technologies dominate the open-source ecosystem.

---

## 📌 Project Objective

The goal of this project is to:

- Collect and analyze file-level data from GitHub repositories
- Visualize trends in file extensions, languages, and repository metadata
- Identify patterns in repository composition and tech stack adoption
- Provide a research-ready dataset for further analysis in academia or industry

---

## 📁 Dataset Schema

**File:** `github_repo_summary.csv`  
Sample structure of the dataset:

| Column Name   | Description                                       |
|---------------|---------------------------------------------------|
| `sample_path` | File path relative to the repository root         |
| `content`     | File content or abstracted summary (optional)     |
| `extension`   | File extension (e.g., `.py`, `.md`, `.js`)        |
| `repo_name`   | Name of the GitHub repository                     |
| `user_name`   | GitHub username or organization                   |
| `stars`       | Number of GitHub stars                            |
| `language`    | Primary programming language used                 |
| `created_at`  | Repository creation date                          |

---

## 🧰 Tools & Technologies

- **GitHub REST API / PyGitHub** – Data extraction
- **Pandas** – Data wrangling and transformation
- **Matplotlib / Seaborn** – Data visualization
- **Jupyter Notebook** – Exploratory analysis

---

## 📊 Analysis Performed

- **Language and Extension Trends**: Top programming languages and file types across repositories
- **Repo Popularity Metrics**: Stars distribution, active organizations, top contributors
- **Temporal Trends**: Growth in stars, commits, or tech stack adoption over years
- **Repository Composition**: Common file structures and usage across open-source projects

---

## 📈 Visualizations Suggested

- **Stacked Area Chart** – Stars and forks over time
- **Bar Plots** – Top file extensions, active contributors, most used languages
- **Network Graph** – Advanced visualization for repo dependencies or collaboration
- **Heatmaps** – Correlation between stars, language, file count, and other metrics

---

## 🎓 Research Applications

This project is designed to support:

- 📘 Academic research on open-source software ecosystems
- 🧪 Software engineering studies of project structures
- 🧠 Tech trend analysis by data science professionals
- 🏢 Enterprise-level audits of OSS contributions

##🙋‍♂️ Author

Atharva Shinde
-📧 sbjitatharvas@gmail.com
-🔗 LinkedIn
-🌐 Portfolio

