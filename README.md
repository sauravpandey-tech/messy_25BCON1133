# messy_25BCON1133

# Student Grade Report & Cursor Rules Experiment

This repository contains a Python script (`messy.py`) that processes student test scores to generate grade reports, calculate class averages, and identify top performers. It serves as a benchmark experiment to compare AI code generation **without Cursor rules** versus **with Cursor rules**[cite: 2, 3].

---

## Prompts Used in Experimentation

The following prompts were executed in the Cursor workspace during development[cite: 2, 3]:

1. **Baseline Prompt:**
   > *"Add a function that counts how many students scored above the class average."*[cite: 2, 3]

2. **Comparison & Rules Setup Prompt:**
   > *"Add a function that counts how many students scored above the class average. Use the same prompt again in a fresh conversation after the rules file has been created, then compare the two."*[cite: 2, 3]

3. **Workflow & Rule Execution Prompt:**
   > *"I'll check the project, the create-rule skill, and how the above-average count is handled so we can add the function and set up a rules file for a later comparison."*[cite: 2, 3]

---

## Repository Structure

```text
.
├── .cursor/          # Cursor rules and workspace configurations[cite: 2, 3]
├── messy.py          # Script for grade processing and class analytics
└── README.md         # Project documentation and prompt tracking
