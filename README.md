# SpaceX Launch Data Collection and Wrangling

This project focuses on collecting, processing, and preparing SpaceX launch data for exploratory data analysis and machine learning tasks.

The dataset was obtained from the SpaceX REST API and supplementary static JSON sources provided through the IBM Data Science Capstone course. The project demonstrates data acquisition, API integration, data cleaning, feature engineering, and dataset preparation using Python.

## Project Objectives

* Collect SpaceX launch data from APIs and static JSON files
* Extract relevant launch information, including rocket, payload, core, and launch site details
* Clean and transform raw data into a structured format
* Handle missing values and inconsistencies
* Prepare the dataset for downstream analysis and predictive modeling

## Dataset Features

The final dataset includes information such as:

* Flight number
* Launch date
* Booster version
* Payload mass
* Orbit type
* Launch site
* Core reuse information
* Landing outcome
* Launch success status

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Requests
* JSON
* REST APIs

## Project Structure

```text
├── jupyter-labs-spacex-data-collection-api-v2.ipynb
├── dataset_part_1.csv
├── requirements.txt
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/spacex-data-collection.git
cd spacex-data-collection
```

Create and activate a virtual environment:

```bash
python -m venv .venv

# Windows
.venv\Scripts\activate

# macOS/Linux
source .venv/bin/activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
jupyter-labs-spacex-data-collection-api-v2.ipynb
```

Run the notebook cells sequentially to collect, process, and export the cleaned dataset.

## API Note

The SpaceX API may occasionally return Cloudflare-related errors such as HTTP 521 or HTTP 525. If this occurs, use the provided static JSON dataset included in the notebook to complete the data collection process.

## Output

The notebook generates a cleaned dataset:

```text
dataset_part_1.csv
```

This dataset can be used for exploratory data analysis, visualization, and machine learning tasks.

## Future Work

* Perform exploratory data analysis (EDA)
* Build predictive models for launch success
* Create interactive visualizations
* Develop dashboards using Plotly or Dash

## License

This project is intended for educational purposes as part of the IBM Data Science Capstone course.
