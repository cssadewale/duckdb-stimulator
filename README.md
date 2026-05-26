# DuckDB Simulator 🦆

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![DuckDB](https://img.shields.io/badge/DuckDB-Simulator-FFC23C?style=flat&logo=duckdb)
![Platform](https://img.shields.io/badge/Platform-Web-green.svg)
![Version](https://img.shields.io/badge/Version-1.0.0-purple.svg)

**DuckDB Simulator** is a powerful, client-side SQL and data analytics workbench that runs completely in your browser. Engineered by **Adewale Samson Adeagbo** (Data Scientist, EdTech Builder, and Founder of HMG Concepts), this platform replicates the analytical capabilities, speed, and UI of DuckDB, but requires absolutely no backend, no APIs, and zero subscription costs.

Designed specifically to run heavy analytics in constrained environments, DuckDB Simulator brings the power of an expert SQL workbench directly to any device — even an Android tablet. 

---

## 👨‍💻 About the Developer

**Adewale Samson Adeagbo** is an AI-Augmented Solutions Developer and Educator with over 15 years in Nigerian classrooms. Driven by a burning conviction that deep-seated problems in education can be solved with technology, he studied Computer Science Education at Lagos State University and advanced his skills via the 3MTT programme.

He doesn't just write code; he thinks clearly, observes deeply, and leverages AI as a force multiplier to operate competently in any domain.

- **Founder:** HMG Concepts (HMG Academy, HMG Technologies, HMG Media)
- **Philosophy:** *"Learning Deliberately. Teaching Authentically."*
- **Connect:** [LinkedIn](https://linkedin.com/in/adewalesamsonadeagbo) | [GitHub](https://github.com/cssadewale) | [Portfolio](https://cssadewale.pages.dev)

---

## 🌟 Key Features

1. **DuckDB-Style Execution Environment**
   Runs a high-performance in-browser analytical SQL engine optimized for heavy, repetitive workloads. Replicates the efficiency and layout of DuckDB tools.

2. **Advanced Query Editor**
   - Syntax highlighting & Auto-completion.
   - Line numbers & syntax error-handling.
   - Multi-tab support to handle multiple simultaneous queries.

3. **Visual Query Builder**
   Construct complex analytical queries visually without writing a single line of SQL. Add `SELECT` columns and `WHERE` conditions dynamically.

4. **Seamless Data Import & Export (CSV/Parquet)**
   Load massive datasets directly from your local machine into the virtual table engine, or export your query results as CSV for external visualizations.

5. **Macro Recording & Automation**
   Automate repetitive workflows. Record sequences of operations and play them back instantly without manual re-typing.

6. **Schema & Table Inspector**
   Navigate databases seamlessly with an automatic table-and-view sidebar. Includes live row-count tracking and schema introspection.

7. **Scalable Data Pagination**
   Handles rendering thousands of rows via a smart paginated view, featuring instantaneous column sorting and single-click copy-to-clipboard.

8. **Query History & Bookmarks**
   Auto-saves every executed query to your local history and allows you to bookmark frequently used scripts so you never lose your progress.

---

## 🚀 Deployment Guide

Deploying DuckDB Simulator is incredibly straightforward because it runs 100% locally in the browser. 

### Prerequisites
- A modern web browser (Chrome, Firefox, Edge, Safari, Brave, etc.)
- (Optional) A local web server or a static site host (like GitHub Pages, Cloudflare Pages, Vercel) if you want to host it online.

### Step-by-Step Deployment

**Option 1: Run Locally (Zero Setup)**
1. Clone this repository or download the `duckdb-simulator.html` file.
2. Double-click the `duckdb-simulator.html` file to open it in your default web browser.
3. The application is completely fully functional offline.

**Option 2: Host on GitHub Pages (Free)**
1. Create a new repository on your GitHub account.
2. Upload the `duckdb-simulator.html` (you can rename it to `index.html` for easier access).
3. Go to your repository **Settings**.
4. Scroll down to the **Pages** section on the left sidebar.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select the `main` branch and the `/ (root)` folder, then click **Save**.
7. In a few minutes, GitHub will provide you with a live URL (e.g., `https://cssadewale.github.io/duckdb-simulator`).

**Option 3: Host on Cloudflare Pages (Free)**
1. Log in to your Cloudflare dashboard and navigate to **Pages**.
2. Click **Create a project** -> **Connect to Git**.
3. Select the repository containing your `duckdb-simulator.html` (renamed to `index.html`).
4. Set the build settings (leave build command blank, and build output directory to the root `/`).
5. Click **Save and Deploy**. Cloudflare provides a globally fast CDN for your application.

---

## 🤝 Contributing
We welcome contributions! Please see the [`CONTRIBUTING.md`](CONTRIBUTING.md) file for detailed guidelines on how to submit pull requests, report bugs, and suggest features.

## 🛡️ Security
Security is a top priority. Because the app runs client-side, your data never leaves your browser unless you explicitly export it. Please review [`SECURITY.md`](SECURITY.md) for vulnerability reporting.

## 📜 Changelog
Curious about what's new? Check out the [`CHANGELOG.md`](CHANGELOG.md) for version history.

---
**DuckDB Simulator** — Engineered with deliberate intent by HMG Technologies.
