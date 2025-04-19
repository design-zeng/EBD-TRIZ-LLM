# 🔧 Enhancing TRIZ through Environment-Based Design Methodology Supported by a Large Language Model

This repository contains a Python implementation of the TRIZ enhancement through Environment-Based Design Methodology Supported by a Large Language Mode, which is presented in:

1. Mohammadi, A. & Zeng, Y. (2025). Enhancing TRIZ through Environment-Based Design Methodology Supported by a Large Language Model. *AI EDAM, 39*.

which was evolved from the following:

2. Zeng, Y. (2004). Environment-based formulation of design problem. *Journal of Integrated Design and Process Science, 8(4)*, 45-63.
3. Wang, M., & Zeng, Y. (2009). Asking the right questions to elicit product requirements. *International Journal of Computer Integrated Manufacturing, 22(4)*, 283-298.
4. Zeng, Y. (2015).  Environment-based design (EBD): A methodology for transdisciplinary design. *Journal of Integrated Design and Process Science, 19(1)*, 5-24.
5. Zeng, Y. (2021). Environment: The first thing to look at in conceptual design. *Journal of Integrated Design and Process Science, 24(1)*, 45-66.
6. Yang, J., Zeng, Y., Ekwaro-Osire, S., Nispel, A., & Ge, H. (2022). Environment-based life cycle decomposition (eLCD): Adaptation of EBD to sustainable design. *Journal of Integrated Design and Process Science, 24(2)*, 5-28.

If you use this implementation in your work, please add a reference/citation to the paper:

```bibtex
@article{pan2021self,
  title={Enhancing TRIZ through Environment-Based Design Methodology supported by a large language model},
  author={Mohammadi, Ali and Zeng, Yong},
  journal={AI EDAM},
  volume={39},
  pages={ex},
  year={2025},
  publisher={Cambridge University Press}
}
```

## 📜 Abstract

This project introduces an integrated conceptual design framework combining **TRIZ**, **Environment-Based Design (EBD)**, and **Large Language Models (LLMs)**. The proposed system assists designers through a structured pipeline—clarifying design problems, extracting functional relationships, and generating innovative ideas—using automation via Python and LangChain.

---



---

## 🚀 Features

- **Structured Workflow:** From problem analysis to solution generation in 6 clear stages
- **EBD-Powered Questioning:** Automated question generation to understand vague design problems
- **Semantic Answer Processing:** Uses LLM to break down design semantics and lifecycle
- **Interaction Extraction Engine:** Identifies relationships between elements using verb parsing
- **Functional Analysis via TRIZ:** Breaks down harmful/useful interactions for contradiction resolution
- **Creative Ideation:** Applies TRIZ's 40 inventive principles with GPT-3.5 API
- **Evaluation Built-in:** Analyzes novelty, variety, quality, and quantity of generated ideas

---

## 🧠 Methodology Overview

The framework follows a 6-stage pipeline:

1. **Input Design Problem:** Natural language design goal (e.g., "design a house that can fly")
2. **Generate Questions:** Based on EBD 5WH logic using GPT
3. **Answer Questions:** Semantic and lifecycle-based answers via LLM
4. **Extract Interactions:** Action-based relationships in `(subject + verb + object)` form
5. **Functional Analysis:** Detect tools, objects, and their effects
6. **TRIZ-Based Ideation:** Use contradiction format to generate ideas using TRIZ's 40 principles

> 🔧 Built with [LangChain](https://www.langchain.com/) and [OpenAI GPT-3.5 API](https://platform.openai.com/).
-----------
🧪 How to Use It


To run this project, you'll need an OpenAI API key.

First, Set Your API Key:
import os
os.environ["OPENAI_API_KEY"] = "YOUR_OPENAI_API_KEY"

Then, Run the Design Pipeline Step-by-Step

Follow the 6-stage process described in the paper and demonstrated in the notebook:

-Input your design problem

-Use the model to generate structured questions (Stage 1)

-Answer the questions (Stage 2)

-Extract key interactions from the answers (Stage 3)

-Generate a functional analysis and identify contradictions (Stage 4–5)

-Generate ideas (Stage 6)

Each function in the notebook is designed to be used interactively and sequentially to support a guided conceptual design process.

---


🤝 Contributing
We welcome ideas, collaborations, and improvements! Open an issue or submit a pull request to contribute.



📬 Contact
For inquiries and academic collaboration:

Ali Mohammadi – alimohammadi.aimi@gmail.com

Yong Zeng – yong.zeng@concordia.ca


📄 License
🔒 License will be made available upon paper acceptance.
📢 For academic and research purposes only.

