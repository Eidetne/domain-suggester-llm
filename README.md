# Domain Name Suggestion with LLMs

This project explores the fine-tuning of open-source Large Language Models (LLMs) to generate *safe, brandable, and constraint-compliant domain names* for businesses.  
The workflow includes dataset creation, model development with LoRA, evaluation using an *LLM-as-a-Judge* framework, and systematic model version comparison.

---

## 📑 Contents

- notebooks/domain_suggester_experiments.ipynb → Main Jupyter Notebook with all experiments and evaluations.  
- data/ → Synthetic and augmented datasets used for fine-tuning.  
- models/ → Saved model checkpoints (v1 baseline, v2 improved).  
- results/ → Evaluation CSVs and generated figures (failure analysis, score comparisons, etc.).  
- report/ → Final technical report (.docx) and optional presentation (.pptx).  

---

## ⚙️ Installation

Clone the repository:

```command line
git clone https://github.com/Eidetne/domain-suggester-llm.git
cd domain-suggester-llm
