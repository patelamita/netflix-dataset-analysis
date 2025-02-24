# Netflix Titles Analysis Project

## Overview
This project analyzes Netflix's content library to understand content distribution, regional preferences, and temporal trends. The analysis includes data cleaning, exploratory analysis, visualization, and insights about Netflix's content strategy.

## Dataset Description
The dataset contains Netflix titles with the following information:

- Show ID
- Type (Movie/TV Show)
- Title
- Director
- Cast
- Country
- Date added
- Release year
- Rating
- Duration
- Listed in (genres)
- Description
- Normalized date

## Project Structure
```
movies_tvshows_analysis/
│
├── notebooks/
│   └── netflix_titles.ipynb
│ 
├── .gitignore
│
├── README.md
│
└── requirements.txt
```

## Requirements
- Python 3.x
- Required packages:
  - pandas
  - numpy
  - matplotlib
  - seaborn

## Installation
1. Clone the repository:
```bash
git clone [repository-url]
cd movies_tvshows_analysis
```

2. Create Virtual Environment file
 ```bash
python env -m virtualenv env
env\scripts\activate
```

3. Install required packages:
```bash
pip install -r requirements.txt
```

1. Data Cleaning and Preprocessing
- Date formatting
- Missing value handling

2. Exploratory Data Analysis
- Content type distribution
- Rating analysis
- Release year trends
- Genre distribution
- Regional content analysis

3. Visualizations
- Content addition trends
- Rating distribution
- Genre popularity charts
- Regional content maps
- Release year patterns


## Genre Analysis
Top genres include:
- Dramas
- Comedies
- Action & Adventure
- International content

## Regional Distribution
Primary production countries:
- United States
- India
- United Kingdom
- Japan

## Usage
Open the Jupyter notebook:

bashCopyjupyter notebook netflix_titles.ipynb

- Run the cells sequentially to:
- Load and process the data
- Generate visualizations
- View analysis results