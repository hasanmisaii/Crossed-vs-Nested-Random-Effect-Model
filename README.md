# Crossed vs Nested Random Effect Models

This repository contains educational notebooks that explain the differences between crossed and nested random effect models through practical examples in both R and Python.

## Overview

Random effects models are essential tools in statistics for analyzing data with hierarchical or grouped structures. Understanding when to use crossed versus nested random effects is crucial for proper model specification and interpretation.

### Crossed Random Effects
- Multiple random effects that are not hierarchically nested
- Each level of one factor can occur with each level of another factor
- Example: Students can be taught by multiple teachers, and teachers can teach multiple students

### Nested Random Effects  
- One random effect is nested within another in a hierarchical structure
- Levels of one factor only occur within specific levels of another factor
- Example: Students nested within classrooms, classrooms nested within schools

## Repository Contents

- `crossed_vs_nested_python.ipynb` - Python implementation with examples using statsmodels and visualization
- `crossed_vs_nested_R.ipynb` - R implementation with examples using lme4 and ggplot2
- `requirements.txt` - Python dependencies
- `requirements_R.txt` - R dependencies

## Getting Started

### Python Environment
```bash
pip install -r requirements.txt
jupyter notebook crossed_vs_nested_python.ipynb
```

### R Environment
```r
# Install required packages listed in requirements_R.txt
install.packages(c("nlme", "lme4", "ggplot2", "dplyr", "tidyr"))
# Open crossed_vs_nested_R.ipynb in Jupyter with R kernel
```

## Key Learning Objectives

1. Understand the conceptual differences between crossed and nested random effects
2. Learn to identify when each model type is appropriate
3. Practice implementing both models in R and Python
4. Interpret and compare model results
5. Visualize the structure and results of each model type

## Examples Covered

- **Crossed Design**: Student performance across multiple teachers and subjects
- **Nested Design**: Student performance within schools and classrooms
- **Model Comparison**: When to choose one approach over the other
- **Practical Interpretation**: Making sense of random effects output
