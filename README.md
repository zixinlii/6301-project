# Visualizing the Effects of Tailored Interventions on Mammography Screening

This project is a small web-based dashboard that visualizes data from a randomized trial of mammography screening interventions. The goal is to show how tailored **mail** and/or **phone** reminders influence:

- The **age distribution** of women in the study  
- **6-month mammography compliance** across intervention groups  
- **Follow-up cognitive stage** (Precontemplation, Contemplation, Action) by intervention group  

The dashboard is implemented as a single HTML file using **Plotly.js** for interactive charts and **PapaParse** for client-side CSV loading.

---

## Files

- `index.html` – main dashboard page (HTML + CSS + JavaScript)
- `mammography_data.csv` – randomized trial data used by the visualizations

---

## How to Run the Project

There is no build step or backend. The page only needs a modern web browser and internet access (to load Plotly and PapaParse from CDNs).

### Option 1: GitHub Pages / Static Hosting

1. Make sure `index.html` and `mammography_data.csv` are in the **same folder** in your repository.
2. Push the repository to GitHub.
3. Enable **GitHub Pages** for the repo (branch: `main` or `master`, source: `/root`).
4. Visit the GitHub Pages URL – the dashboard should load automatically and fetch `mammography_data.csv` from the same directory.

### Option 2: Run Locally with a Simple HTTP Server

Some browsers block `file://` AJAX requests, so it is safer to use a local server:

1. Clone or download this repository.
2. In a terminal, `cd` into the folder that contains `index.html` and `mammography_data.csv`.
3. Start a simple server, for example with Python:

   ```bash
   python -m http.server 8000

AI Usage Statement

This project was developed with the assistance of AI tools (such as ChatGPT) for tasks including debugging, code explanation, documentation drafting, and improving clarity of written text. All final decisions regarding code structure, visualization design, and analytical interpretation were made by me. The dataset analysis, visualization logic, and implementation were conducted independently, and AI tools were used only as supportive resources, not as automated code generators for the final system.
