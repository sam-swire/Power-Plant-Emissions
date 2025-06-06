# EPA Emissions Data Pipeline
This project is an end-to-end data pipeline and analysis toolkit for U.S. power plant emissions using publicly available EPA datasets. Built as a capstone project at Northwestern, it automates the ingestion, transformation, and analysis of emissions data—converting raw files to optimized Parquet format and enabling GPT-based insights via LangChain.

## 🚀 Features
- Ingests and cleans raw EPA emissions data
- Converts large CSV datasets to Parquet for efficient querying
- Merges data chunks into final structured files
- Automates the full ETL process with modular Python scripts
- Integrates with a GPT-powered assistant (via LangChain) for interactive querying

## 📁 Project Structure
energy-emissions-pipeline/
├── autodownload_.py          # Automated data download scripts
├── merge_chunk_.py           # Chunk merging and consolidation scripts
├── final_merge_and_clean.py   # Final transformation script
├── gpt_integration/           # LangChain-based GPT interface
├── data/                      # (gitignored) Raw and processed datasets
├── LICENSE                    # MIT License
└── README.md

