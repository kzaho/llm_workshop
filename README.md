# Exploring Open-Source LLM: Medical Record Analysis

## Workshop Overview
Join our 30-minute workshop to explore the specialized use of Llama2-70B.

- **Specialized LLM Application**: Learn how a fine-tuned Llama2-70B model is applied in medical record analysis.
- **Practical Demonstration**: Experience live setup and usage of this LLM (CPU and GPU instance), analyzing different scenarios to utilize LLM (getting keywords, topic modeling).

Ideal for IT professionals, this workshop underlines the importance of using fine-tuned LLM for specific industry needs.

## Data for the Workshop
Before starting the workshop, please download the "Medical Transcriptions" data from [Kaggle](https://www.kaggle.com/datasets/tboyle10/medicaltranscriptions).

## Jupyter Notebooks
The workshop includes three Jupyter notebooks, which you can access and view directly in this repository:
1. [**llm_cpu.ipynb**](llm_cpu.ipynb): Can be run on a standard laptop. Demonstrates basic usage of Llama2-70B on CPU.
2. [**llm_gpu.ipynb**](llm_gpu.ipynb): Optimized for running on Google Colab with a T4 GPU. Focuses on utilizing GPU acceleration.
3. [**adv_llm_gpu.ipynb**](adv_llm_gpu.ipynb): Intended for cloud environments like GCP. Requires a machine with specifications like n1-standard-16 (16 vCPUs, 60 GB RAM) and 4 NVIDIA T4 GPUs (USD 1,645 hourly, ~0.005 USD per record -> 5k records = 25 USD) for advanced processing and analysis.

## License
This project is open-sourced under the [MIT License](LICENSE).
