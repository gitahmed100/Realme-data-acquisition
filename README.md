# 📱 Data Acquisition Project – Realme Website Scraping

This project demonstrates a full data acquisition pipeline using **Google Search + SerpAPI** to scrape relevant pages from the Realme Egypt website. The extracted links are modeled as a network graph and visualized using **NetworkX** and **Matplotlib** in both 2D and 3D formats.

---

## 🚀 Features

- 🔍 Scrape Google search results using SerpAPI  
- 🌐 Extract and link Realme-related web pages  
- 🧠 Visualize relationships as a graph (2D & 3D)  
- 🧮 Centrality analysis using KDE heatmap  

---

## 📊 Visualizations

- 📉 2D Network Graph  
- 🌡️ KDE Heatmap of Node Centrality  
- 🧩 3D Mesh Network Graph  

---

## 🛠️ How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook final_acq_project.ipynb
Replace the placeholder API key with your own from SerpAPI.

📦 Dependencies
See requirements.txt.

⚠️ Note
Requires a SerpAPI key.

Built with 📍 Egypt region (gl="eg" in search parameters).

yaml
Copy
Edit

Then click **Commit changes**.

---

### 2. 📸 (Optional but Powerful) Add Images to README

You can run your notebook, save the plots as `.png` files, and drag them into the GitHub repo. Then you can embed them in your README like:

```markdown
## 📸 Sample Visualization

![2D Graph](realme_graph_2d.png)
