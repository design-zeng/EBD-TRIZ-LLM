# 🔧 Enhancing TRIZ through Environment-Based Design Methodology Supported by a Large Language Model

This repository accompanies the research paper:

**"Enhancing TRIZ through Environment-Based Design Methodology Supported by a Large Language Model"**  
*Ali Mohammadi, Yong Zeng – Concordia University*

---

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

📝 Citation
If you use this repository or our framework in your research, please cite:
@article{mohammadi2025enhancing,
  title={Enhancing TRIZ through Environment-Based Design Methodology Supported by a Large Language Model},
  author={Mohammadi, Ali and Zeng, Yong},
  journal={To Appear},
  year={2025}
}

🤝 Contributing
We welcome ideas, collaborations, and improvements! Open an issue or submit a pull request to contribute.



📬 Contact
For inquiries and academic collaboration:

Ali Mohammadi – alimohammadi.aimi@gmail.com

Yong Zeng – yong.zeng@concordia.ca


📄 License
🔒 License will be made available upon paper acceptance.
📢 For academic and research purposes only.

