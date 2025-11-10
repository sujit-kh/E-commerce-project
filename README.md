# E-commerce-project
ecomm-etl-pipeline/
│
├── data/
│ ├── raw/ # original CSVs (do NOT commit large files to git)
│ │ ├── orders_2024.csv
│ │ ├── customers_2024.csv
│ │ └── products_2024.csv
│ └── processed/ # cleaned CSVs (committed small samples)
│ └── orders_cleaned.csv
│
├── notebooks/ # Jupyter notebooks for exploratory analysis
│ ├── 01_explore.ipynb
│ ├── 02_transform.ipynb
│ └── 03_load_to_sql.ipynb
│
├── scripts/ # modular scripts to run pipeline
│ ├── extract.py
│ ├── transform.py
│ ├── load.py
│ └── run_pipeline.py
│
├── sql/
│ ├── create_tables.sql
│ └── analytics_queries.sql
│
├── dashboard/
│ └── powerbi_dashboard.pbix
│
├── pipeline_diagram/
│ └── architecture.png
│
├── tests/ # optional: unit/integration tests for scripts
│
├── requirements.txt
├── README.md # this file
└── .gitignore
