
# The Empathetic Code Reviewer

An AI-powered, multi-language **empathetic code review assistant** that not only finds issues in code but also explains them **kindly**, **educationally**, and **contextually** just like a great senior developer would.

---

##  Features
- **Supports multiple languages**: Python, JavaScript, Java, C++ (easily extendable)
- **Two input modes**:
  - Upload a `.json` file containing code & review comments
  - Manually type/paste code and comments in Colab
- **Empathetic feedback** with:
  - Positive rephrasing of feedback
  - Educational "Why" explanations
  - Code improvement suggestions
  - Relevant resource links
- **Multi-AI Model Support**: Google Gemini (default), OpenAI GPT-4o, Anthropic Claude 3.5
- **Professional Markdown Reports** with clear formatting
- **Colab Preview** of generated reports

---

##  Technologies Used
- **Language Models (LLMs)**: Google Gemini 1.5 Pro (default)
- **Python** for orchestration
- **Jupyter/Google Colab** for interactive execution
- **Markdown** for formatted outputs

---

## Project Structure


├── notebook.ipynb        # Main Jupyter Notebook
├── sample\_input.json     # Python example
├── sample\_input\_js.json  # JavaScript example
├── sample\_input\_java.json# Java example
├── sample\_input\_cpp.json # C++ example
└── README.md             # Project documentation



---

##  Quick Start (Google Colab)
1. **Open in Colab**: [Click here to open](https://colab.research.google.com)
2. **Upload notebook.ipynb** to Colab.
3. **Run Cells 1–7** for setup and functions.
4. From **Cell 8 onwards**:
   - **Option 1**: Upload one of the provided `.json` files
   - **Option 2**: Type code and comments manually
5. View:
   - **Markdown Preview in Colab** (Cell 11)
   - Downloadable `.md` report (Cell 10)

---

##  JSON Input Format
Each `.json` must have:
```json
{
  "code_snippet": "Your code here...",
  "review_comments": [
    "Comment 1",
    "Comment 2"
  ]
}
````

---

##  Example Reports

The system produces reports like:

```markdown
# Empathetic Code Review Report
Generated: 2025-08-14
Language: Python

## Comment: "Variable 'u' is a bad name"
Positive Rephrasing: Great job keeping variables short! Let's make it more descriptive...
Why: Improves readability...
Suggested Improvement: ...
Resources: [PEP 8](https://peps.python.org/pep-0008/#function-and-variable-names)
```

---

##  Hackathon Highlights

This project demonstrates:

* **Advanced Prompt Engineering**
* **Cross-language Code Understanding**
* **Empathetic AI Interaction Design**
* **Practical Developer Tooling**

---

##  Author

**Rishi Pramod**
B.Tech, 4th Year | IIIT Kottayam

```

