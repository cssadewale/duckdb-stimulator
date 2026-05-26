# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2026-05-23

### Added
- **Complete Re-Architecture to DuckDB Simulator:** Transitioned the legacy `SQLab v6` interface into a fully-fledged DuckDB Analytics Simulator.
- **DuckDB UI/UX Theme:** Implemented the classic DuckDB Yellow (`#FFC23C`) and deep dark styling theme across the entire application for maximum immersion.
- **Detailed Features Guide Modal:** Added a comprehensive system guide accessible from the header explaining features (Query Builder, Macros, Import/Export, etc.).
- **Developer Persona Integration:** Dynamically embedded the profile, contact details, and philosophy of **Adewale Samson Adeagbo** (Founder of HMG Concepts) directly into the platform to reinforce the "Built for Education" narrative.
- **Deployment Documentation:** Authored a robust, unambiguous `DEPLOYMENT.md` guiding users through offline, GitHub Pages, and Cloudflare Pages deployment setups.
- **Repository Documentation:** Added comprehensive `README.md`, `SECURITY.md`, `CONTRIBUTING.md`, and this `CHANGELOG.md` tailored for open-source scale.

### Changed
- Refactored internal labeling to mirror DuckDB's syntax and analytics focus.
- Upgraded the CSS variables and responsive breakpoints for the unified DataTech workspace experience.

### Maintained
- Retained core functionalities from the original SQLab to prevent breaking changes:
  - Synchronous WebAssembly execution architecture.
  - Multi-tab advanced query editor.
  - Visual Query Builder (`WHERE` conditions, `SELECT` logic).
  - Macro recording engine.
  - Paginated high-volume data viewer.
  - Seamless CSV import and structure-mapping tools.

---
*Built deliberately by HMG Technologies.*
