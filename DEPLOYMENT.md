# Enterprise Deployment Manual (Zero-Cost Architecture)

The **DuckDB Enterprise Simulator** brings powerful, analytical data processing strictly into the client side. By leveraging WebAssembly and JavaScript, this application perfectly replicates the speed, UI, and CLI of DuckDB without relying on centralized backend databases, paid AI APIs, or expensive compute instances.

**Cost of Deployment:** ₦0.00 forever.

By leveraging enterprise-grade edge networks (like Cloudflare Pages or GitHub Pages), you can secure and deploy this platform globally for internal teams, classrooms, or your data science portfolio.

---

## 🏗 Why this Architecture? (The Enterprise Edge)
1. **Zero Egress Architecture:** Data imported by users (CSV/Parquet simulation via WASM) *never* leaves their browser. Computation happens entirely in their local RAM.
2. **Infinite Scalability:** Because there is no backend server to overload, 1 user or 100,000 users cost exactly the same to host.
3. **Exact Replica Features:** Includes the famous DuckDB Terminal CLI overlay (`💻 CLI Shell`), Live Memory Profiling, Execution Plan analysis, and Data Quality scanning directly in the browser.

Here are the detailed, unambiguous steps to deploy the system securely.

---

## 🛡️ Method 1: Enterprise Deployment (Cloudflare + Zero Trust)
*Best for internal tools, classroom exams, or private staff analytics. Provides global CDN caching and enterprise authentication.*

### Step 1: Push Code to GitHub
1. Log into your GitHub account ([github.com/cssadewale](https://github.com/cssadewale)).
2. Click the **"+"** icon (top right) and select **New repository**.
3. Name the repository (e.g., `duckdb-enterprise-simulator`). Set it to **Private**.
4. Rename `duckdb-simulator.html` to `index.html` on your computer.
5. Upload the `index.html` and the markdown documentation files.
6. Click **Commit changes**.

### Step 2: Connect to Cloudflare Pages
1. Create a free account at [Cloudflare Dashboard](https://dash.cloudflare.com) and navigate to **Workers & Pages**.
2. Click **Create Application**, then go to the **Pages** tab.
3. Click **Connect to Git** and authorize your GitHub account.
4. Select the `duckdb-enterprise-simulator` repository.
5. Click **Begin setup**.
6. In the build settings:
   - **Framework preset:** None
   - **Build command:** (Leave blank)
   - **Build output directory:** `/` (or leave blank)
7. Click **Save and Deploy**.
8. Cloudflare will instantly generate a fast, secure URL (e.g., `https://duckdb-enterprise.pages.dev`).

### Step 3: Implement Enterprise Access Control (Cloudflare Zero Trust)
*Ensure only authorized students/staff can access the tool:*
1. In Cloudflare, navigate to **Zero Trust** -> **Access** -> **Applications**.
2. Click **Add an Application** and select **Self-hosted**.
3. Enter your deployed Cloudflare Pages URL.
4. Set up an **Access Policy** (e.g., "Allow emails ending in `@hmgconcepts.com`" or whitelist specific student emails).
5. Now, anyone visiting the URL must securely authenticate via an email One-Time Password (OTP) before the DuckDB Simulator loads. You get Enterprise IAM for free.

---

## 🌐 Method 2: Public Portfolio Deployment (GitHub Pages)
*Best if you want it publicly accessible alongside your existing `cssadewale.pages.dev` sites.*

1. Follow Step 1 above, but ensure the repository is set to **Public**.
2. In your repository, click the **Settings** tab (the gear icon near the top right).
3. On the left sidebar, click **Pages**.
4. Under "Build and deployment" -> "Source", ensure **Deploy from a branch** is selected.
5. Under "Branch", select the dropdown that says *None*, choose **`main`**, and leave the folder as `/ (root)`.
6. Click **Save**.
7. Wait 2-3 minutes. Your platform is now permanently live and securely hosted by Microsoft via GitHub Pages.

---

## 💻 Running Offline / Locally
If you are in a classroom without internet access:
1. Download the `index.html` file to your tablet, phone, or laptop.
2. Double click it to open in Google Chrome or Brave.
3. The platform, including the CLI shell, query builder, and data importer, will run flawlessly offline using the cached WebAssembly engine.

---
*Architected deliberately by HMG Technologies.*
