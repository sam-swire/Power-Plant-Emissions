# EPA Emissions Data Pipeline
This project is an end-to-end data pipeline and analysis toolkit for U.S. power plant emissions using publicly available EPA datasets. Built as a capstone project at Northwestern, it automates the ingestion, transformation, and analysis of emissions data—converting raw files to optimized Parquet format and enabling GPT-based insights via LangChain.

## 🚀 Features
- Ingests and cleans raw EPA emissions data
- Converts large CSV datasets to Parquet for efficient querying
- Merges data chunks into final structured files
- Automates the full ETL process with modular Python scripts
- Integrates with a GPT-powered assistant (via LangChain) for interactive querying

## 📁 Project Structure
<pre lang="markdown"><code>
energy-emissions-pipeline/
├── autodownload_*.py             # Automated data download scripts
├── merge_chunk_*.py              # Chunk merging and consolidation scripts
├── final_merge_and_clean.py      # Final transformation script
├── gpt_integration/              # LangChain-based GPT interface
├── data/                         # (gitignored) Raw and processed datasets
├── LICENSE                       # MIT License
└── README.md
</code></pre>

## 🧠 Motivation
EPA emissions data is valuable but fragmented. This project makes it accessible, clean, and interactive—bridging environmental data science and AI tools to support further analysis, policy research, and educational use.

## 💻 Getting Started
1. **Clone the repo**:
   ```bash
   git clone https://github.com/sam-swire/energy-emissions-pipeline.git
   cd energy-emissions-pipeline

2.	Install requirements (optional for GPT use):
pip install -r requirements.txt

3.	Run the ETL pipeline:
python autodownload_X.py       # Replace with appropriate download script
python merge_chunk_6_into_final.py
python final_merge_and_clean.py

4.	Launch GPT assistant:
cd gpt_integration
python chatbot.py

## 📄 License
This project is licensed under the MIT License.

