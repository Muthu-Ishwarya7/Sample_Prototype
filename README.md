# Dashboard Prototype

This project is a prototype HTML webpage designed to display dashboards using embedded Power BI reports. It provides a clean and user-friendly interface with **tabbed navigation**, allowing stakeholders to switch between multiple dashboards seamlessly.

---

## 📄 Project Overview

The prototype currently includes the following dashboards:

- **Attrition & Retention Dashboard**
- **Recruitment Tracker Dashboard**
- **Global Sales Dashboard**

Each dashboard is embedded directly from Power BI and viewable in the browser.

---

## 💻 How to Use

### Option 1: View Online (via GitHub Pages)

The dashboard is hosted on GitHub Pages and can be viewed live here:

🔗 **[View Live Prototype](https://muthu-ishwarya7.github.io/Sample_Prototype/)**

### Option 2: Run Locally

To view the dashboard locally:

1. Clone or download this repository
2. Open `index.html` in any web browser (Chrome, Firefox, Edge, etc.)
3. Use the navigation tabs at the top to switch between dashboards

---

## 📁 Files Included

- `index.html` – The main HTML file with embedded Power BI dashboards and tabbed layout
- `README.md` – This documentation file

---

## 📌 Notes

- All dashboards are embedded using Power BI **iframe links**
- The dashboards are **read-only** and intended for **viewing only**
- To replace dashboards:
  - Edit the `iframe` `src` URLs in `index.html` with your own Power BI report links

---

## 🧑‍💼 Created For

This dashboard prototype was developed for **internal review**, **stakeholder presentations**, and **lightweight visualization sharing**. It is ideal for sharing performance metrics in a simplified and visually organized layout.

---

## 🚀 How to Deploy HTML File to GitHub Pages

You can make your HTML site public using **GitHub Pages**. Follow the steps below:

---

### 1. Create a GitHub Repository

1. Go to [https://github.com](https://github.com)
2. Click **New repository**
3. Name the repo (e.g., `dashboard-prototype`)
4. Set visibility to **Public**
5. (Optional) Check **"Add a README file"**
6. Click **Create repository**

---

### 2. Upload Your HTML File

#### 📁 Option A: Upload via GitHub Website

1. Go to your repository
2. Click **Add file > Upload files**
3. Upload your `.html`, `.css`, and other files
4. Click **Commit changes**

#### 🧑‍💻 Option B: Upload via Git (Terminal Method)

If Git is installed on your machine:

bash
# Clone the repo
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Add your HTML files to the folder
git add .
git commit -m "Initial commit"
git push origin main
'''
### 3. Enable GitHub Pages

1. Go to your repository → **Settings**
2. In the left sidebar, click **Pages** (under "Code and Automation")
3. Under **Source**, choose:
   - **Branch**: main
   - **Folder**: / (root)
4. Click **Save**

GitHub will generate a live deployment link within a few seconds.

---

### 4. Access Your Site

Your site will be available at: https://muthu-ishwarya7.github.io/Sample_Prototype/
