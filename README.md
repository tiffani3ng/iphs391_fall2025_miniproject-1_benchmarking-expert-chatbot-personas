````markdown
# Benchmarking Expert Chatbot Personas  
*A Mini-Project on Persona Prompt Engineering and Evaluation Metrics*

![License](https://img.shields.io/badge/license-MIT-blue.svg)  
![Status](https://img.shields.io/badge/status-completed-green.svg)  
![Made with](https://img.shields.io/badge/made%20with-Prompt%20Engineering-orange)

---

## 📖 Overview
This project investigates **how effectively chatbots can roleplay as designed personas** when guided by carefully engineered prompts. The repository contains the full report and supporting files for **IPHS 391: Fall 2025 Mini-Project 1**, focusing on benchmarking persona fidelity through rubric-based evaluation.  

The work explores the **intersection of AI, prompt design, and evaluation metrics**, demonstrating how prompt engineering shapes chatbot behavior and how structured rubrics can assess persona quality.

---

## 🧩 Methodology
1. **Persona Prompt Engineering**  
   - Crafted detailed persona descriptions (background, quirks, conversational style).  
   - Used **explicit constraints** (tone, length, quirks, emojis, formatting rules) to enforce stylistic fidelity.  

2. **Evaluation Framework**  
   - Applied a **custom rubric (0–100 points)** with six weighted factors:  
     1. Persona Alignment (25%)  
     2. Prompt-Bound Fidelity (20%)  
     3. Voice & Style Appropriateness (15%)  
     4. Contextual Responsiveness (15%)  
     5. Creativity & Depth (15%)  
     6. Engagement & Coherence (10%)  

3. **Testing**  
   - Conducted **10-turn chatbot conversations** with the persona.  
   - Scored outputs against rubric criteria.  

---

## 📊 Results
- **Overall Score**: ~67/100  
- **Strengths**:  
  - Responses were coherent and engaging.  
  - Dialogue remained contextually appropriate (roommate-like flow).  
- **Weaknesses**:  
  - Persona-specific quirks (short responses, emoji use, capitalization rules) were inconsistently followed.  
  - Limited integration of backstory details from the prompt.  

**Key Insight:**  
Even with strong prompt engineering, LLMs may drift toward generic conversational styles without explicit reinforcement mechanisms. Structured rubrics highlight these gaps, offering a repeatable way to benchmark persona fidelity.

---

## 📂 Files Description
- **`mp1_chatbot_report.docx`** — Full project report with analysis, rubric, and scoring.  
- **`prompt_persona.txt`** — Persona prompt specification used in the evaluation.  
- **`chat_history.md`** — Transcript of the chatbot conversation.  
- **`chat_rubric.txt`** — Evaluation rubric (weights, factors, scoring criteria).  

---

## 🚀 Usage Instructions
To explore or replicate this project:  

1. Clone the repository:  
   ```bash
   git clone https://github.com/tiffani3ng/iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas.git
   cd iphs391_fall2025_miniproject-1_benchmarking-expert-chatbot-personas
````

2. Open the report and rubric files for details.
3. Run your own chatbot experiments using the `prompt_persona.txt` template.
4. Score conversations against the rubric in `chat_rubric.txt`.

---

## 🧠 Highlight: Persona Prompt Engineering Techniques

* **Constraint-based design**: limiting sentence length, punctuation, and emoji set.
* **Behavioral quirks**: repetition, capitalization emphasis, casual text shorthand.
* **Grounded backstory**: embedding cultural and academic identity to guide responses.
* **Rubric benchmarking**: quantitative scoring for qualitative persona fidelity.

---

## ⚖️ Contributing

Contributions are welcome! Suggestions for rubric refinement, additional personas, or alternative evaluation methods can be submitted via pull requests.

---

## 📜 License

This project is released under the [MIT License](LICENSE).

---

## ✨ Acknowledgments

* Developed as part of **IPHS 391: Fall 2025**.
* Special thanks to peers and instructors for feedback on persona design and evaluation methodology.
