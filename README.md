# Matthew Delamasa Portfolio

A clean GitHug Pages portfolio showcasing projects in machine learning, computer vision, and data engineering.

## Overview

This website was built as a lightweight static portfolio using HTML, CSS, with individual project pages organized in a simple folder structure for easy maintenance and GitHub Pages deployment.

The goal of the site is to present projects in a cleaner, more visual format than a standard GitHub repository alone. Each project includes a dedicated page with:

- project overview
- tools and technology used
- implementation details
- screenshots or media outputs
- links to source code and live demos where available

## Project Categories

### Experimental
Projects focused on model behavior, comparisons, and analytical reasoning

- **Logistic Regression vs Random Forest on Two Classification Tasks**
    - Notebook-based comparison of two classification models across datasets with different structures
    - Emphasis on preprocessing, interpretability, and evaluation beyond raw accuracy

### Fully Deployed
Projects with a working interface and deployment-oriented structure.

- **Recyclable Material Sorting with YOLO and Streamlit**
    - Computer vision application cfor recyclable waste detection
    - Supports image upload, annotated video output, and live detection workflows
    - Built with a custom trained Ultralytics YOLO mode and streamlit frontend

### Data Pipeline
Projects centere on ETL workflows, transformation logic, and structured data outputs.

- **Azure ETL Sales Pipeline**
    - Python ETL workflow inspired by Azure-style raw and processed data layers
    - Loads cleaned outputs into CSV and SQLite

- **PySpark E-Commerce Sales Data Pipeline**
    - Spark-based pipeline for ingesting, cleaning, transforming, and analyzing e-commerce sales data
    - Generated business insight output such as revenue trends and regional summaries

## Tech Used for This Portfolio

- HTML5
- CSS3
- GitHub Pages

## Folder Structure

```
portfolio-site/
├── index.html
├── style.css
├── README.md
├── assets/
│   ├── images/
│   └── videos/
└── projects/
    ├── recycle-sorter.html
    ├── ml-model-comparison.html
    ├── azure-etl-sales-pipeline.html
    └── spark-sales-pipeline.html
```
## Purpose
This site was built to create a more polished and accessible way to present technical projects, with a focus on readability, structure, and practical implementation.

## Author
**Matthew Delamasa**