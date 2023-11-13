# Data_assignment
This assignment focuses on the data analytics of space conjunctions. The goal is to derive high-level insights from a sample data set of predicted conjunctions of active satellites in space. The analytics should be intuitive, represented in an easily understandable format


# Space Conjunction Analysis Tool


## Table of Contents

- [About](#about)
- [Analysis Overview](#analysis-overview)
- [Installation](#installation)


## About

The Space Conjunction Analysis Tool is a Python-based application for analyzing satellite conjunction data. It processes satellite collision probability data, identifies trends, and visualizes insights to help space agencies and satellite operators make informed decisions.

## Analysis Overview

The tool performs the following analyses:

- Identification of most frequent satellite pairs for each conjunction type on specific dates.
- Calculation of maximum and minimum collision probabilities for satellite conjunctions.
- Categorization of conjunctions into risk levels: No Risk, Close Approach, and Collision.

## Installation

Make sure you have Python installed. Clone the repository and install the required dependencies.

```
git clone https://github.com/nithishsingh/Data_Assignment.git
cd Data_Assignment
pip install -r requirements.txt
```

Activate the virtual environment:
On Windows:

```
venv\Scripts\activate 
```
Use code with caution. Learn more
On macOS and Linux:

```source venv/bin/activate ```

Use code with caution. Learn more
Run the Jupyter Notebook for detailed data analysis:

```conjunction_analysis.ipynb```

jupyter notebook conjunction_analysis.ipynb
Use code with caution. Learn more
To visualize the results, 

run the Dash web application:
```python dash_app.py``` or use JuypterDash

Use code with caution. Learn more
Open your web browser and go to http://127.0.0.1:8050/ to view the Dash app.

Please note that you may need to restart the Jupyter Notebook after installing the new dependencies.
