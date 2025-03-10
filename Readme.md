# Rebar Data Processing & Visualization App

This Streamlit-based application processes IFC files containing rebar data, extracts relevant details, and visualizes key metrics such as total rebar length and weight distribution.

## Features
- **IFC File Upload**: Upload an IFC file to extract rebar details.
- **Data Refinement**: Extracts shape, steel grade, bend radius, and calculates estimated weight.
- **Summary Table**: Groups data by nominal diameter and provides total length, total weight, and count.
- **Interactive Plots**: Visualizes total length and total weight by nominal diameter using Plotly.
- **Export Option**: Download the summary table as an Excel file.

## Installation

### Clone the Repository
```sh
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
pip install -r requirements.txt

streamlit run app.py

