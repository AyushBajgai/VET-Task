# VET Task

A data analysis project exploring Australian Vocational Education and Training (VET) data using Python and Jupyter Notebooks.

## Overview

This project analyses VET-related data across several key entities, including:

* Students
* Enrolments
* Organisations
* Contracts

The analysis is supported by a structured Excel dataset and a collection of Jupyter Notebooks, with each notebook focusing on a specific area of the VET data model.

The project is designed to explore, clean, analyse and derive insights from VET datasets using reproducible Python-based data analysis workflows.

## Repository Structure

```text
VET-Task/
│
├── Contract.ipynb
├── Enrolment.ipynb
├── Organisation.ipynb
├── Student.ipynb
├── VET_Data_Task1.xlsx
└── README.md
```

### Notebooks

| Notebook             | Description                                          |
| -------------------- | ---------------------------------------------------- |
| `Student.ipynb`      | Analysis and exploration of student-related VET data |
| `Enrolment.ipynb`    | Analysis of enrolment-related data and patterns      |
| `Organisation.ipynb` | Analysis of VET organisation/provider information    |
| `Contract.ipynb`     | Analysis of contract-related VET data                |

### Dataset

`VET_Data_Task1.xlsx` contains the source data used throughout the analysis.

The notebooks use this dataset as the primary source for data exploration and analysis.

## Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas** – data manipulation and analysis
* **NumPy** – numerical operations
* **Matplotlib** – data visualisation
* **Seaborn** – statistical data visualisation
* **Microsoft Excel / XLSX** – source dataset

> The exact libraries used may vary between notebooks.

## Getting Started

### Prerequisites

Make sure you have Python installed on your system.

It is recommended to use a virtual environment.

### 1. Clone the repository

```bash
git clone https://github.com/AyushBajgai/VET-Task.git
cd VET-Task
```

### 2. Create a virtual environment

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

#### macOS / Linux

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install the required packages

```bash
pip install pandas numpy matplotlib seaborn openpyxl jupyter
```

### 4. Start Jupyter Notebook

```bash
jupyter notebook
```

Open any of the notebooks to explore the analysis.

## Analysis Workflow

The project follows a notebook-based data analysis workflow:

```text
VET_Data_Task1.xlsx
        │
        ▼
   Data Loading
        │
        ▼
 Data Cleaning & Preparation
        │
        ▼
 Data Exploration
        │
        ▼
   Analysis & Queries
        │
        ▼
 Visualisations / Results
        │
        ▼
      Insights
```

Each notebook focuses on a different component of the VET data, allowing the analysis to be separated into logical and manageable sections.

## Project Components

### Student Analysis

`Student.ipynb` focuses on student-level information contained within the VET dataset.

The notebook can be used to explore student records, identify patterns within the data and produce relevant summaries or visualisations.

### Enrolment Analysis

`Enrolment.ipynb` focuses on enrolment records.

This component provides an opportunity to investigate enrolment activity, distributions and relationships between enrolments and other VET entities.

### Organisation Analysis

`Organisation.ipynb` focuses on organisations within the VET ecosystem.

This analysis can be used to explore organisation/provider information and understand how organisations are represented within the dataset.

### Contract Analysis

`Contract.ipynb` focuses on contracts and their associated information.

This notebook provides analysis of contract-related records and their relationships with other entities in the dataset.

## Reproducibility

To reproduce the analysis:

1. Clone the repository.
2. Ensure `VET_Data_Task1.xlsx` is available in the expected project directory.
3. Install the required Python packages.
4. Launch Jupyter Notebook.
5. Run the notebooks from top to bottom.

Running the notebooks sequentially ensures that data preparation, analysis and visualisations are generated consistently.

## Data

The project uses the supplied `VET_Data_Task1.xlsx` workbook as its primary data source.

Because the analysis is based on an educational/task dataset, results should be interpreted within the context of the supplied data rather than treated as a complete representation of the Australian VET sector.

## Purpose

This project demonstrates practical skills in:

* Data loading and preparation
* Data cleaning
* Exploratory data analysis
* Working with relational datasets
* Data aggregation
* Statistical analysis
* Data visualisation
* Extracting meaningful insights from structured data
* Using Python and Jupyter Notebook for reproducible analysis

## Future Improvements

Potential improvements include:

* Adding automated data-validation checks
* Consolidating repeated data-cleaning code into reusable functions
* Adding more interactive visualisations
* Creating a single dashboard summarising the major findings
* Adding automated tests for data-processing steps
* Adding a `requirements.txt` file for easier environment setup
* Documenting individual analytical findings in greater detail

## Author

**Ayush Bajgai**

GitHub: [@AyushBajgai](https://github.com/AyushBajgai)

## Repository

https://github.com/AyushBajgai/VET-Task
