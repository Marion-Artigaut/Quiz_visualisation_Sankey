# Sankey visualisation of Moodle quiz responses

---

## About

This repository supports the UNSW *Teaching News You Can Use* video created by **Marion Artigaut**, School of Civil and Environmental Engineering.

This project provides .ipynb codes to visualise student responses from online quizzes (Moodle and/or Inspera) as Sankey flow diagrams from online quizzes, to help educators quickly identify:

- Ambiguous or confusing quiz questions  
- Persistent misconceptions or learning bottlenecks  
- Potential irregular answer patterns (e.g. AI-assisted responses)  
- Opportunities to refine teaching and feedback  

By following the flow of responses, lecturers can transform raw quiz data into evidence-based insight for continuous improvement of assessment design and teaching practice.

---

## Prerequisites

To use the included Python notebook or scripts, you will need the following Python libraries:

- `pandas` — for data manipulation and analysis  
- `numpy` — for numerical computations  
- `matplotlib` — for static data visualization  
- `plotly` — for interactive data visualization  

Built-in Python modules used:
- `os`
- `os.path`

### Installation

You can install the required libraries using **pip**:

```bash
pip install pandas numpy matplotlib plotly
```

--- 

## Usage

The current code provides examples for:
- Moodle responses reports across multiple weeks

### Example output

![Sample Chart](examples/images/weekly.png)




