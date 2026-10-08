# Jesse Anderson

I build practical automation, data, and tooling systems that make messy
workflows easier to understand and operate.

- Data systems and automation engineer
- BS Chemical Engineering from UIC, with concentrations in Biochemical Engineering and Process Automation, and an MCS from UIUC
- Focused on C#, Rust, Python, VBA, Excel, embedded systems, and data-heavy workflow tooling
- Interested in internal tools, technical systems, and engineering work that improves clarity and leverage

[Website](https://jesse-anderson.net/) ·
[Blog](https://blog.jesse-anderson.net/) ·
[Portfolio](https://portfolio.jesse-anderson.net/) ·
[LinkedIn](https://www.linkedin.com/in/jesse-anderson-a7c5) ·
[ORCID](https://orcid.org/0000-0001-5731-5511)

## Rust and Excel Tooling

**linreg-core**  
Rust linear regression library published across Rust, WebAssembly, Python, VBA, DLL, and Excel XLL surfaces.  
Repo: [jesse-anderson/linreg-core](https://github.com/jesse-anderson/linreg-core) · Packages: [crates.io](https://crates.io/crates/linreg-core), [PyPI](https://pypi.org/project/linreg-core/), [npm](https://www.npmjs.com/package/linreg-core)

**xll-rs**  
Rust runtime and support library for building native Excel XLL add-ins on Windows.  
Repo: [jesse-anderson/xll-rs](https://github.com/jesse-anderson/xll-rs) · Packages: [crates.io](https://crates.io/crates/xll-rs)

**xllgen**  
Proc-macro layer for generating Excel XLL wrappers in Rust.  
Repo: [jesse-anderson/xllgen](https://github.com/jesse-anderson/xllgen) · Packages: [crates.io](https://crates.io/crates/xllgen) · Docs: [docs.rs](https://docs.rs/xllgen/latest/xllgen/)

**xll-utils**  
PE/COFF parsing and export verification utilities for Excel XLL development.  
Repo: [jesse-anderson/xll-utils](https://github.com/jesse-anderson/xll-utils) · Packages: [crates.io](https://crates.io/crates/xll-utils) · Docs: [docs.rs](https://docs.rs/xll-utils/latest/xll_utils/)

**xll-template**  
cargo-generate template that scaffolds a working Excel XLL add-in project in Rust.  
Repo: [jesse-anderson/xll-template](https://github.com/jesse-anderson/xll-template)

**Workbook Radar**  
Excel/VBA auditing and tracing tool focused on workbook risk, dependency graphs, and VBA flow analysis.  
Private project, no public site or repo.

## Web Apps and Sites

**Tools**  
Durable collection of 50+ small web utilities published for everyday use.  
Live Site: [tools.jesse-anderson.net](https://tools.jesse-anderson.net/tools.html) · Repo: [jesse-anderson/Tools](https://github.com/jesse-anderson/Tools)

- Rust/WebAssembly: [DBSCAN Visualizer](https://tools.jesse-anderson.net/tools/dbscan-visualizer.html), [Linear Regression](https://tools.jesse-anderson.net/tools/linear-regression.html), [AI Image Detector](https://tools.jesse-anderson.net/tools/ai-image-detector.html)
- Process and controls: [PID Playground](https://tools.jesse-anderson.net/tools/pid-playground.html), [Control Valve Sizing](https://tools.jesse-anderson.net/tools/control-valve-sizing.html), [Psychrometric Calculator](https://tools.jesse-anderson.net/tools/psychrometric-calculator.html), [Steam Tables](https://tools.jesse-anderson.net/tools/steam-tables.html), [Moody Chart Reader](https://tools.jesse-anderson.net/tools/moody-chart.html), [Uncertainty Propagation](https://tools.jesse-anderson.net/tools/uncertainty-propagation.html)
- Data: [DuckDB Playground](https://tools.jesse-anderson.net/tools/duckdb-playground.html), [Parquet Viewer](https://tools.jesse-anderson.net/tools/parquet-viewer.html), [SQLite Viewer](https://tools.jesse-anderson.net/tools/sqlite-viewer.html), [CSV Profiler](https://tools.jesse-anderson.net/tools/csv-profiler.html)
- Excel and documents: [Excel Formula Extractor](https://tools.jesse-anderson.net/tools/excel-formula-extractor.html), [PDF Diff Checker](https://tools.jesse-anderson.net/tools/pdf-diff.html), [OCR Text Extractor](https://tools.jesse-anderson.net/tools/ocr-text-extractor.html), [Scientific Graph Compare](https://tools.jesse-anderson.net/tools/scientific-graph-digitizer.html)
- Biochemical engineering: [Oral Multi-Dose Simulator](https://tools.jesse-anderson.net/tools/oral-multidose.html), [HED Calculator](https://tools.jesse-anderson.net/tools/hed-calculator.html), [Toxicology Body Burden](https://tools.jesse-anderson.net/tools/toxicology-and-body-burden.html), [Stoichiometry Calculator](https://tools.jesse-anderson.net/tools/stoichiometry-calculator.html), [Yogurt CFU/g Estimator](https://tools.jesse-anderson.net/tools/yogurt-cfu-estimator.html), [Species Doubling Reference](https://tools.jesse-anderson.net/tools/species-doubling-reference.html), [Creatine Lab](https://tools.jesse-anderson.net/tools/creatine-lab.html)
- Workflow and diagrams: [Process Flow Mapper](https://tools.jesse-anderson.net/tools/process-flow-mapper.html), [Sankey Diagram Builder](https://tools.jesse-anderson.net/tools/sankey-diagram.html), [Meeting Planner](https://tools.jesse-anderson.net/tools/meeting-planner.html)

**Oak Park Crime Map**  
Public-facing crime map and data exploration project for Oak Park.  
Live Site: [opcrime.jesse-anderson.net](https://opcrime.jesse-anderson.net/crime_map) · Repo: [jesse-anderson/Oak-Park-Crime](https://github.com/jesse-anderson/Oak-Park-Crime)

**Oak Park Crime Dashboard**  
Descriptive, source-linked data science dashboard over public Oak Park Police Department daily activity bulletins.  
Live Site: [opcrimeds.jesse-anderson.net](https://opcrimeds.jesse-anderson.net/) · Repo: [jesse-anderson/OP-Crime-Dashboard-Public](https://github.com/jesse-anderson/OP-Crime-Dashboard-Public)

**N-Back**  
N-back working memory trainer built as a polished end-result project.  
Live Site: [nback.jesse-anderson.net](https://nback.jesse-anderson.net/)

**SpeedReader**  
Browser-based RSVP speed reader with a Rust/WebAssembly core, ORP highlighting, and adaptive pacing.  
Live Site: [speedreader.jesse-anderson.net](https://speedreader.jesse-anderson.net/)

**Home Environmental Sensor Network**  
ESP32 boards around the house logging particulates (PM1 through PM10), temperature, humidity, air pressure, light, and soil conditions since June 2024. Readings flow through a cron Worker into precomputed artifacts with no runtime database. The public view publishes daily statistics on a 30-day delay, alongside an outdoor baseline from the city sensor network.  
Live Site: [sensors.jesse-anderson.net/public](https://sensors.jesse-anderson.net/public)

**Portfolio**  
Project portfolio site.  
Live Site: [portfolio.jesse-anderson.net](https://portfolio.jesse-anderson.net/) · Repo: [jesse-anderson/Portfolio](https://github.com/jesse-anderson/Portfolio)

**Blog**  
Engineering, science, and tech writing.  
Live Site: [blog.jesse-anderson.net](https://blog.jesse-anderson.net/)

## Data Modeling (dbt)

**Oak Park Crime Data Docs**  
Lineage, column documentation, and test coverage for the Oak Park crime dataset: two ingest streams, 19 models, and a parity check against the Python it reimplements.  
Live Site: [opcrime.jesse-anderson.net/dbt-docs](https://opcrime.jesse-anderson.net/dbt-docs/) · Repo: [jesse-anderson/Oak-Park-Crime](https://github.com/jesse-anderson/Oak-Park-Crime)

**Oak Park Crime Dashboard Data Docs**  
Lineage, column documentation, and test coverage for the Oak Park crime dashboard: 33 models, 570 documented columns, 100 tests.  
Live Site: [opcrimeds.jesse-anderson.net/dbt-docs](https://opcrimeds.jesse-anderson.net/dbt-docs/) · Repo: [jesse-anderson/OP-Crime-Dashboard-Public](https://github.com/jesse-anderson/OP-Crime-Dashboard-Public)

**Meal Kit Analytics**  
dbt project modeling a weekly meal delivery business end to end, from raw landing tables through to BI-ready marts: 477,000 boxes, 20,000 customers, 24 months.  
Live Site: [mealkit.jesse-anderson.net](https://mealkit.jesse-anderson.net/) · Repo: [jesse-anderson/mealkit_analytics](https://github.com/jesse-anderson/mealkit_analytics)

## Embedded and Other

**SPS30_ESP32**  
Generalized Python library for the SPS30 particulate matter sensor on ESP32.  
Repo: [jesse-anderson/SPS30_ESP32](https://github.com/jesse-anderson/SPS30_ESP32)

**VBA_Batch_Reactor**  
Excel to Word VBA reporting pipeline with Python-generated synthetic batch reactor data.  
Repo: [jesse-anderson/VBA_Batch_Reactor](https://github.com/jesse-anderson/VBA_Batch_Reactor)

**Scientific_Paper_Graph_Comparison_Tool**  
Python tool for comparing control vs treatment values read off published graphs on a percentage basis. A JavaScript version runs in the browser as Scientific Graph Compare.  
Live Site: [Scientific Graph Compare](https://tools.jesse-anderson.net/tools/scientific-graph-digitizer.html) · Repo: [jesse-anderson/Scientific_Paper_Graph_Comparison_Tool](https://github.com/jesse-anderson/Scientific_Paper_Graph_Comparison_Tool)
