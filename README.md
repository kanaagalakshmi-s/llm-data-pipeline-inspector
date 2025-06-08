
# 🧠 AI-Powered Data Pipeline Auditor

This project analyzes Azure Data Factory (ADF) pipeline JSONs using an open-source LLM in Google Colab. It provides intelligent architecture reviews, detects bottlenecks, and suggests performance optimizations.

## 🚀 Features
- Upload and parse ADF pipeline JSON exports
- Generate analysis using TinyLlama (or other open-source models)
- Runs fully inside a Google Colab notebook
- No proprietary or paid LLMs used

## 📄 Sample Input
You can use the included `sample_adf_pipeline.json` to test immediately.

## 🛠 How It Works
1. Installs `transformers` and loads a TinyLlama model
2. Accepts pipeline export JSON files from your ADF environment
3. Parses the pipeline and generates a summarization prompt
4. Outputs detailed AI feedback:
   - Pipeline purpose
   - Performance risks
   - Optimization tips
   - Design rating

## 🧪 Try It Now
1. [Download the Colab notebook](./AI_Pipeline_Auditor_Colab.ipynb)
2. Upload it to [Google Colab](https://colab.research.google.com/)
3. Upload a pipeline JSON
4. Run the notebook cells and view the LLM's intelligent analysis

## 📦 Dependencies
```bash
pip install transformers accelerate
```

## 🧠 Model
Using:
- [`TinyLlama/TinyLlama-1.1B-Chat-v1.0`](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0)
- Optional: Swap with `mistralai/Mistral-7B-Instruct-v0.1` on GPU

## 🤝 Contributions Welcome
Want to support Synapse pipelines or visualize with Streamlit? Fork it and improve!

## 📌 Author
Kanaagalakshmi Senthil · Azure Cloud Engineer
