# Contributing to DuckDB Simulator

Thank you for your interest in contributing! This project is built on the philosophy of **"Learning Deliberately. Teaching Authentically."** We welcome contributions that align with our goal to provide robust, free, and accessible data science tools for Nigerian students, educators, and the global tech community.

## How Can I Contribute?

### 1. Reporting Bugs
If you find a bug, please create a GitHub Issue. Be sure to include:
- A clear descriptive title.
- Steps to reproduce the behavior.
- Your browser and operating system version.
- Screenshots if applicable.

### 2. Suggesting Enhancements
We want to keep this tool lightweight, free, and robust. If you have an idea for a feature (that does not require expensive backend infrastructure or paid APIs):
- Open an Issue labeled `enhancement`.
- Explain how the enhancement improves the platform for the end-user.

### 3. Submitting Pull Requests
If you want to write code and fix issues:
1. **Fork the repository** to your own GitHub account.
2. **Create a new branch** for your feature or bug fix:
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. Make your changes in the `duckdb-simulator.html` file (or other relevant scripts).
4. **Test your changes** thoroughly in a modern browser to ensure nothing is broken (specifically query execution, CSV imports, and macros).
5. **Commit your changes** with descriptive messages:
   ```bash
   git commit -m "Add responsive sidebar toggle"
   ```
6. **Push to the branch**:
   ```bash
   git push origin feature/amazing-feature
   ```
7. **Open a Pull Request** against the `main` branch of this repository.

## Coding Guidelines
- **Vanilla over Frameworks:** Keep it vanilla. This platform specifically avoids heavy frameworks (React, Angular) to maintain a single-file, deploy-anywhere architecture.
- **Client-Side Only:** Do not introduce server-side logic (e.g., PHP, Node.js endpoints, or database connections).
- **Styling:** Follow the existing CSS variable structure (`--a1` for primary colors, `--bg` for backgrounds) to maintain UI consistency.

Let's build tools that solve real problems.
