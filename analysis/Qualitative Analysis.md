# Phase 3 — Step 2: Qualitative Analysis

This section examines *how* the LLMs frame the season across different hypotheses and conditions by looking at narrative patterns, tone, and evidence use.  
We focus on **three required areas**:

1. Patterns in language choices  
2. Hallucination / fabrication tendencies  
3. Cherry-picking of statistics to fit narratives  

---

## 1. Patterns in Language Choices

### **1.1 Positive framings**
Prompts:  
- **H1_positive**  
- **H3_positive_hypothesis**

Across all three models (GPT-4, Claude, Gemini), positive framings consistently use:

- **Growth language**  
  - "momentum", "improvement", "confidence", "resilience"  
- **Team cohesion phrasing**  
  - "worked together", "found rhythm", "built stability"  
- **Selective highlighting of strong wins**  
  - especially G1 (+12), G14 (+12), G9 (+6), G18 (+6)  
- **Softening of losses**  
  - described as “learning moments” or “setbacks”

Positive prompts avoid specifics about heavy losses (like −15 vs #2) unless necessary.

---

### **1.2 Negative framings**
Prompts:  
- **H1_negative**  
- **H3_negative_hypothesis**

Negative narratives emphasize:

- **Defensive breakdowns**  
  - repeated references to “gaps,” “inconsistency,” “pressure moments”  
- **Margin-of-defeat focus**  
  - G16 (−15), G4 (−8), G17 (−5)  
- **Framing close losses as failures to close out**  
  - G8 (−1), G19 (−1), G13 (−3)

Negative framing downplays mid-season wins and rarely acknowledges momentum.

---

### **1.3 Neutral framings**
Prompts:  
- **H1_neutral**, **H2_neutral**, **H3_neutral**

Neutral framings tend to:

- Present wins and losses sequentially
- Highlight variability (“mixed season,” “inconsistent results”)
- Avoid emotionally charged words
- Mention both strengths and weaknesses within the same sentence

Neutral summaries look like small factual reports without strong positioning.

---

### **1.4 Model-specific stylistic differences (important for bias analysis)**

Across all 81 responses:

- **GPT-4**:  
  - Most structured, analytical, and compressed  
  - Uses more “trend” language (“performance patterns,” “trajectory”)  

- **Claude-3-Opus**:  
  - Most philosophical/emergent  
  - Uses reflective words (“meaningful movement,” “navigating limitations”)  

- **Gemini-1.5-Pro**:  
  - Shorter, more direct  
  - Emphasiz
