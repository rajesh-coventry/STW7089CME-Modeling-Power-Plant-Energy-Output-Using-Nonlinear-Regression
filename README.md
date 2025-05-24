# **STW7089CME-Modeling-Power-Plant-Energy-Output-Using-Nonlinear-Regression:**

## **Repository Structure:**
```
.
├── assignment_report.pdf
├── README.md
├── STW 7089CEM Introduction To Statistical Methods For Data Science.pdf
├── assignment_report/
│   ├── assignment_report.aux
│   ├── assignment_report.fdb_latexmk
│   ├── assignment_report.fls
│   ├── assignment_report.log
│   ├── assignment_report.out
│   ├── assignment_report.pdf
│   ├── assignment_report.synctex.gz
│   ├── assignment_report.tex
│   ├── m1.png
│   ├── m10.png
│   ├── m11.png
│   ├── m5.png
│   ├── m6.png
│   ├── m7.png
│   ├── m8.png
│   ├── p1.png
│   ├── p2.png
│   ├── p3.png
│   ├── p4.png
│   ├── p5.png
│   ├── p6.png
│   ├── r21.png
│   ├── softwarica_covventry.png
│   └── ...
├── core_concepts/
├── main_code/
├── tests/
```
This repository holds all the code, supporting files, and documentation for the project titled **“Modeling CCPP Power Plant Energy Output Using Nonlinear Regression”**, created as part of the coursework for the *STW 7089CEM – Introduction to Statistical Methods for Data Science* module.

The goal of this project was to select a better-performing nonlinear regression model to predict the net hourly energy output of a Combined Cycle Power Plant (CCPP), based on various environmental factors like temperature, pressure, and humidity.

## **What’s in Here?**

* **`assignment_report.pdf`:**
  This is the final report we submitted. It includes the background, methodology, model selection process, results, and conclusions from the project.

* **`README.md`:**
  The file we’re reading right now. It explains what the project is about and where to find everything.

* **`STW 7089CEM Introduction To Statistical Methods For Data Science.pdf`:**
  Course material provided by the university. Useful if you want to understand the theory behind the techniques we used.

### **`assignment_report/`:**

This folder contains everything related to the LaTeX version of the project report:

* **`assignment_report.tex`** – The main LaTeX file that generates the final PDF.
* **`assignment_report.pdf`** – A duplicate copy of the compiled report stored here for reference.
* **Build files** – These include `.aux`, `.log`, `.out`, etc., generated automatically when compiling the LaTeX document.
* **Figures** – PNG files like `m1.png`, `p2.png`, `r21.png`, etc., used for plots, diagrams, or illustrations in the report.

This folder is where the visual and structural work behind the report happens.

### **`core_concepts/`:**

This directory includes notes, scripts, and explanations that cover the foundational ideas used in the project—like nonlinear modeling approaches, statistical diagnostics, or preprocessing steps. Think of this as the study or scratchpad area.

### **`main_code/`:**

All the actual modeling code lives here. If you're looking to dive into how we processed the data, trained models, and visualized results, this is the place you want to visit.

**Key file:**

* **`(CODE_ONLY)-Modeling_Power_Plant_Energy_Output_Using_Nonlinear_Regression.ipynb`**
  A Jupyter notebook with all the main code sections—from data loading to plotting, predictions, and ABCs.

* **`(CODE_plus_Explaination)-Modeling_Power_Plant_Energy_Output_Using_Nonlinear_Regression.ipynb`**
  A Jupyter notebook with all the main code sections explained in detail—from data loading to plotting, predictions, ABCs, and many more.

* **`(CODE_ONLY)-Modeling_Power_Plant_Energy_Output_Using_Nonlinear_Regression.Rmd`**
  An R Markdown notebook with all the main code sections—from data loading to plotting and, predictions.

There may also be additional scripts or data files that support the core analysis.

### **`tests/`:**

This is where we experimented with ideas, tested code functionality, or validated our models. It’s helpful if you want to understand the trial-and-error process we went through to fine-tune our models.

## **License and Usage:**

This repository is intended for educational purposes. If you plan to reuse or reference this work, please follow the course or university guidelines and give appropriate credit.
