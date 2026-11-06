# SpaceX Launch Data Collection and Wrangling

A Jupyter Notebook project focused on collecting and preparing Falcon 9 launch records for exploratory analysis and machine learning.

This notebook forms part of the IBM Data Science Professional Certificate capstone learning pathway.

## Objective

Launch records combine mission, rocket, payload, and booster information from different sources. The aim is to turn those records into a consistent tabular dataset that can support downstream analysis.

## Data Sources

- SpaceX REST API
- Supplementary static JSON resources referenced in the IBM capstone material

## Workflow

1. Retrieve launch information.
2. Extract mission, payload, rocket, core, and launch-site attributes.
3. Convert nested records into a tabular structure.
4. Handle missing or inconsistent values.
5. Prepare features for later analysis and modelling.

## Technologies

Python, Pandas, NumPy, Requests, JSON, and Jupyter Notebook.

## Repository Contents

```text
.
├── SpaceX launch data collection and wrangling project.ipynb
└── README.md
```

## How to Run

Install the packages imported by the notebook, then launch Jupyter:

```bash
jupyter notebook
```

Open `SpaceX launch data collection and wrangling project.ipynb` and run the cells sequentially.

**Note:** The source API or hosted static data may change or become unavailable. The repository does not currently include the `dataset_part_1.csv` and `requirements.txt` files described in the previous README.

## Next Steps

- Add a reproducible dependency specification.
- Record the dataset source and extraction date.
- Export and document the cleaned dataset.
- Link this work to the subsequent SpaceX EDA and modelling repositories.

## Author

Jehosaphat Brobbey Impiani  
[GitHub](https://github.com/Slimjoey56)