# Task_08_Descriptive_Stats

## 🔁 How to Reproduce these Experiments

This repository includes all materials needed to fully reproduce the LLM bias evaluation study. Follow the steps below.

---

### **1. Use the Provided Prompt Templates**

Navigate to: 

prompts/

This folder contains all prompt variants for:

- H1 – Framing Bias  
- H2 – Selection / Neutral Bias  
- H3 – Confirmation Bias  
- H4 – Rank-Based Bias  

Each prompt includes the complete Syracuse Women’s Lacrosse dataset to ensure grounded responses.

---

### **2. Query the Language Models**

For every prompt:

1. Open **GPT-4**, **Claude 3 Opus**, and **Gemini 1.5 Pro**  
2. Start a **new chat for each run** to avoid context contamination  
3. Paste the prompt exactly as written  
4. Run **3 samples per model per prompt**

This yields:
9 outputs per prompt condition
81 total outputs across all hypotheses

---

### **3. Log All Outputs Using the Structured Schema**

Open:

results/Structured_Log.xlsx

For each model output, record:

- run_id  
- model_name  
- model_version  
- prompt_id  
- hypothesis_id  
- condition  
- sample_index  
- timestamp  
- prompt_text  
- response_text  

This ensures consistency across all analyses.

---

### **4. Run the Analysis**

Go to:

analysis/

There you will find:

- **Quantitative_Analysis.md** – sentiment scoring, keyword counts, statistical comparisons  
- **Qualitative_Analysis.md** – narrative patterns, framing differences, cherry-picking  
- **Validation_Against_Ground_Truth.md** – checks for factual accuracy and fabrication  
- **ground_truth_summary.md** – dataset reconstruction and summary  

Follow each file’s steps to reproduce the full analysis pipeline.

---

### **5. Compare Results to the Final Report**

The final outputs, patterns, and interpretations are documented in:

REPORT.md

Your reproduced analysis should match:

- Sentiment differences between framing types  
- Model-specific narrative behaviors  
- Game cherry-picking patterns  
- Rank visibility effects  
- Fabrication rate differences  

---

### ✔ Reproduction Complete

Once these steps are completed, anyone can regenerate the full experiment from scratch, including prompts, model outputs, analyses, and the final report.




