# COMP1844 Public Transport Network Coursework

## Student

Name: Le Dinh Minh Phu  
Module: COMP1844 – Information Analysis and Visualisation

## Project Description

This project uses Python and the NetworkX graph data structure to
represent and visualise a section of the London Underground network.

The project contains three tasks:

- Task 1: Recreate the provided three-line transport network.
- Task 2: Expand the network to at least five lines with interchange stations.
- Task 3: Calculate numerical statistics from the station distances.

Station distances were approximated using Google Earth and are shown
in kilometres.

## Requirements

- Python 3.14.0
- Jupyter Notebook
- NumPy
- Pandas
- NetworkX
- Matplotlib

## Environment Setup

Create a virtual environment:

```bash
py -3.14 -m venv .venv
```

Activate the environment on Windows:

```bash
.venv\Scripts\activate
```

Install the required libraries:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Running the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open the following file:

```text
cw.ipynb
```

Select:

```text
Run All
```

Alternatively, open `cw.ipynb` in Visual Studio Code and select
**Run All**.

## Project Files

- `cw.ipynb`: complete source code for Tasks 1, 2 and 3.
- `standard-tube-map.pdf`: TfL map used as a visual reference.
- `notebook_outputs/`: generated visualisation images.
- `requirements.txt`: required Python libraries.

## Data Sources

- Transport for London Tube map.
- Google Earth distance measurement tool.