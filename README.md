# Visualizing the Effects of Tailored Interventions on Mammography Screening

This project is an interactive web-based dashboard that visualizes data from a randomized trial examining how tailored **mail** and **phone** reminders influence mammography screening behavior among women. The dashboard presents:

- **Age distribution** of study participants  
- **6-month mammography compliance** across intervention groups  
- **Follow-up cognitive stage distribution**  
  (Precontemplation, Contemplation, Action)

The goal of this project is to show how different behavioral interventions affect screening adherence and readiness to change, using clear and interactive visual analytics.

---

## 🌐 Live Demo

**https://zixinlii.github.io/6301-project/**

The dashboard runs directly in the browser and requires no installation.

---

## 📁 Files in This Repository

├── index.html # Main dashboard page (HTML + CSS + JavaScript)
├── mammography_data.csv # Randomized trial dataset used by all visualizations
└── README.md # Project documentation


---

## 🚀 How to Run the Project

This project uses only client-side code. There is **no backend or build process**.

You can run it in **two ways**:

### **Option 1 — GitHub Pages (Already Enabled)**

1. Put `index.html` and `mammography_data.csv` in the same folder.
2. Push to GitHub.
3. Enable GitHub Pages (source = `/root`).
4. Open the published URL.

Your live website is already here:  
**https://zixinlii.github.io/6301-project/**

### **Option 2 — Run Locally (Recommended for Testing)**

Because browsers block `file://` AJAX requests, please use a simple local server:

```bash
python -m http.server 8000

Then visit,
http://localhost:8000/
