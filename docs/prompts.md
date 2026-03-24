# 🤖 Prompt Engineering — AI Fitness Analytics Project

This document describes the real prompt engineering workflow used in this project.

Instead of generating the dashboard directly, ChatGPT was used as a **prompt engineering assistant**, while Lovable was responsible for building the dashboard and application.

---

## 🧠 Approach

The process followed this flow:

Dataset generated using NotebookLM → ChatGPT used to design a structured prompt → Prompt executed in Lovable → Iterative refinements applied directly in Lovable

This approach simulates a real-world workflow where AI is used as a co-pilot.

---

## 🧾 Prompt Creation (ChatGPT → Lovable)

The initial step was to use ChatGPT to transform the dataset into a structured prompt for Lovable.

### Prompt used in ChatGPT:

```text
Use this CSV dataset to generate a prompt for Lovable with the goal of creating a dashboard focused on strength training and running analysis.

Suggest:
- Analytical scenarios;
- Filters;
- Charts and tables;
- A coherent storytelling structure.

```

### Context provided:

The dataset contains 50 records and 19 variables, including:

- Training category and type
- Muscle groups
- Training goals
- Athlete level
- Intensity and heart rate zones
- Sets, repetitions, duration, and rest
- Weekly frequency
- Benefits and risks
- Equipment

### Outcome:
ChatGPT generated a structured and detailed prompt ready to be used in Lovable.

## 📊 Generated Prompt (Used in Lovable)

The generated prompt included:

- Dashboard structure (Overview, Strength, Running, Planning, Risks)
- KPIs and metrics
- Suggested visualizations (bar charts, pie charts, scatter plots, tables)
- Expected insights
- Global filters

This prompt served as the foundation for the dashboard creation in Lovable.

## 🔁 Iterative Refinement (Lovable)

After generating the initial dashboard, multiple refinements were applied directly in Lovable.

### Key iterations:
1. Analytical Improvements
- Added dynamic analytical summaries below dashboard sections;
- Improved storytelling across pages;
- Enhanced insights visibility.

2. Interactivity
- Enabled cross-filtering between charts
- Added interactive filters with badges

3. Data Exploration Enhancements
- Added sortable tables (ascending/descending);
- Refined axis ordering (e.g., duration, intensity, levels).

4. Visualization Improvements
- Replaced charts with more meaningful visuals (e.g., heatmaps);
- Adjusted scatter plot formatting and axis structure.

5. Custom Components
- Adjusted fatigue risk visualization layout;
- Added explanatory sections for user interpretation.

6. Advanced Features
Introduced AI Fitness concepts:
- Virtual Coach;
- Training plan generator;
- Performance Score;
- Fatigue Risk Index;
- Evolution simulator.

### Outcome:
The dashboard evolved into a data-driven fitness analytics platform.

## 📌 Key Learnings
ChatGPT is highly effective for structuring prompts, not just generating outputs
The quality of the prompt directly impacts the dashboard quality
Iteration is essential to reach a product-level result
Combining data + UX + AI instructions leads to better systems

## 🧰 Tools Used
- NotebookLM → dataset and knowledge generation;
- Lovable → dashboard and application development;
- ChatGPT → prompt engineering and documentation support.

ChatGPT was used as an assistant to structure prompts and refine the project, but not to directly generate the dashboard.

🚀 Final Insight

This project demonstrates a real-world workflow: 

AI is not just used to generate outputs, but to design better systems through structured prompts and iteration.
