# belly-button-challenge
# Belly Button Biodiversity Dashboard

This interactive dashboard visualizes data on belly button biodiversity, allowing users to explore microbial species found in human navels. It enables users to view demographic metadata, analyze bacterial compositions, and observe trends through dynamic visualizations.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Use](#how-to-use)
- [Project Structure](#project-structure)
- [Live Deployment](#live-deployment)
- [Installation Instructions](#installation-instructions)
- [Acknowledgments](#acknowledgments)

---

## Features
- **Bar Chart**: Displays the top 10 Operational Taxonomic Units (OTUs) for each selected individual.
- **Bubble Chart**: Visualizes all OTUs with marker size indicating abundance and color coded by OTU ID.
- **Demographic Metadata**: Provides key demographic information about the selected individual.
- **Dynamic Interactivity**: Updates all visualizations when a new sample is selected.

---

## Technologies Used
- **HTML/CSS**: For layout and styling.
- **JavaScript**: For interactivity and data processing.
- **D3.js**: To fetch data from the JSON file and manipulate the DOM.
- **Plotly.js**: For rendering bar and bubble charts.
- **GitHub Pages**: For deploying the project as a static website.

---

## How to Use
1. Open the deployed application: [Belly Button Biodiversity Dashboard](https://rich-willet.github.io/belly-button-challenge//)
2. Select a sample ID from the dropdown menu.
3. View:
   - **Top 10 Bacteria Cultures Found** in the bar chart.
   - **Bacteria Cultures Per Sample** in the bubble chart.
   - **Demographic Information** in the metadata panel.

---

## Project Structure
