# 📘 Scaling Instruction Fine-Tuning in LLMs – Supplementary Material

This repository contains comparative tables and structured datasets supporting the review paper:

**Title**: *Scaling Instruction Fine-Tuning in LLMs: A Comparative Review of Datasets, Pipelines, and Open-Source Implementations*  
**Author**: Ayush Kumar  
**Affiliation**: B.Tech, Computer Science and Engineering (AI & ML), Vellore Institute of technology, Vellore, India 

**Email**: ayushkr09@gmail.com

## 📝 About the Paper

Instruction fine-tuning is critical for aligning Large Language Models (LLMs) with human intent, enabling them to perform a wide range of tasks more reliably and ethically. This paper presents a comparative review of the latest datasets, pipelines, methodologies, and open-source implementations used in instruction fine-tuning, including models like **Alpaca**, **Vicuna**, **Zephyr**, and techniques like **SFT**, **RLHF**, and **DPO**.

📄 **[Read the Full Paper (#)]**

## 📂 Supplementary CSV Tables

| File Name                           | Description                                                        |
|-------------------------------------|--------------------------------------------------------------------|
| `table1_llms_with_params.csv`       | Overview of instruction-tuned LLMs and their parameters            |
| `table2_llms_comparison.csv`        | Comparative table of LLMs based on dataset, tuning, and features   |
| `table3_datasets.csv`               | Overview of instruction tuning datasets (type, size, applications) |
| `table4_finetuning_methods.csv`     | Comparison of fine-tuning methodologies: SFT, RLHF, DPO            |

## 📌 Citation

If you find this work useful, please cite the paper:

@article{Kumar2025InstructionTuning,
  title={Scaling Instruction Fine-Tuning in LLMs: A Comparative Review of Datasets, Pipelines, and Open-Source Implementations},
  author={Ayush Kumar},
  journal={SN Computer Science},
  year={2025},
  note={Available at GitHub: https://github.com/ayushkr09/instruction-tuning-review-resources}
}

## Usage
- You can load the CSVs using pandas in Python:

python
import pandas as pd

llms = pd.read_csv("table2_llms_comparison.csv")
print(llms.head())

## 📬 Contact
For collaboration, questions, or feedback, feel free to reach out:

📧 Email: [ayushkr09@gmail.com]
🌐 LinkedIn: [www.linkedin.com/in/ayushkumarsoftwareengineer]

## 📃 License
This project is licensed under the [MIT License](LICENSE) – you are free to use and distribute with attribution.
