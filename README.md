# Exploring Open-Source LLM: Medical Record Analysis

## Workshop Overview
Welcome to our 30-minute workshop focused on "Exploring Open-Source LLM: Medical Record Analysis". In this workshop, we delve into the specialized application of the Llama2-70B model, a fine-tuned large language model, in the context of medical record analysis.

### What You Will Learn
- **Specialized LLM Application**: Gain insights into how the Llama2-70B model, fine-tuned for specific use-cases, can be applied to analyze medical records efficiently and accurately.
- **Practical Demonstration**: Experience a live setup and usage of the Llama2-70B model on both CPU and GPU instances. Learn through practical examples that demonstrate different scenarios where LLM can be utilized effectively, including keyword extraction and topic modeling from medical data.

## Workshop Contents
1. **Introduction to Llama2-70B**
   - Overview of the model
   - Special features and capabilities in medical analysis

2. **Setup and Configuration**
   - Setting up Llama2-70B on CPU and GPU instances
   - Configurations for optimal performance

3. **Practical Demonstration**
   - Analyzing medical records with Llama2-70B
   - Techniques for keyword extraction
   - Approaches to topic modeling in medical data

4. **Q&A Session**
   - Open discussion and questions

## Prerequisites
- Basic understanding of large language models (LLMs)
- Familiarity with medical terminologies (beneficial but not mandatory)

## Data for the Workshop
Before starting the workshop, please download the "Medical Transcriptions" data from [Kaggle](https://www.kaggle.com/datasets/tboyle10/medicaltranscriptions). This dataset, scraped from mtsamples.com, will be used in the Jupyter notebooks during the workshop.

## Jupyter Notebooks
The workshop includes three Jupyter notebooks, which you can access and view directly in this repository:
1. [**llm_cpu.ipynb**](llm_cpu.ipynb): Can be run on a standard laptop. Demonstrates basic usage of Llama2-70B on CPU.
2. [**llm_gpu.ipynb**](llm_gpu.ipynb): Optimized for running on Google Colab with a T4 GPU. Focuses on utilizing GPU acceleration.
3. [**adv_llm_gpu.ipynb**](adv_llm_gpu.ipynb): Intended for cloud environments like GCP. Requires a machine with specifications like n1-standard-16 (16 vCPUs, 60 GB RAM) and 4 NVIDIA T4 GPUs for advanced processing and analysis.

## Installation and Setup
For participants who wish to follow along with the practical demonstration, ensure you have the necessary environment set up on your machine. Detailed instructions are provided in the [installation guide](/installation.md).

## Contributing
We welcome contributions and suggestions to improve this workshop. If you have ideas or feedback, please feel free to open an issue or submit a pull request.

## License
This project is open-sourced under the [MIT License](LICENSE).

## Acknowledgments
Special thanks to all the contributors and participants who make this workshop possible. Your enthusiasm and insights are invaluable to the community.
