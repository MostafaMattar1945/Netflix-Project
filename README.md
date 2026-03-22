# Netflix Data Analysis

This project is an exploratory data analysis (EDA) of a Netflix dataset, performed as part of a Python data analysis learning journey. The notebook demonstrates data loading, cleaning, transformation, and visualization to extract meaningful insights about movies and TV shows available on Netflix.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Project Structure](#project-structure)
- [Steps and Analysis](#steps-and-analysis)
- [Results and Insights](#results-and-insights)
- [How to Run](#how-to-run)
- [License](#license)

## Overview

The goal of this project is to analyze a Netflix dataset to answer questions such as:
- Which year had the most movies and TV shows added?
- What is the distribution of movies vs. TV shows?
- Who are the most prolific directors?
- What are the most common ratings?
- Which countries produce the most content?
- How long are the movies on Netflix (mean and max duration)?

The analysis involves data cleaning, handling missing values, converting data types, and creating visualizations to present findings.

<img width="867" height="769" alt="image" src="https://github.com/user-attachments/assets/cb7cab80-89ae-4bd6-8f06-dc200d919a99" />
<img width="881" height="817" alt="image" src="https://github.com/user-attachments/assets/3594dc78-a60e-4a55-a397-913ac85aecf4" />
<img width="792" height="718" alt="image" src="https://github.com/user-attachments/assets/491dc341-e320-4e19-8243-a098252e0a2d" />
<img width="761" height="770" alt="image" src="https://github.com/user-attachments/assets/b045c2e0-6404-45de-9023-7bc1bd6e8cd5" />
<img width="736" height="761" alt="image" src="https://github.com/user-attachments/assets/f7dcf576-f734-44fd-8948-ff3f0fd356d8" />






## Dataset

The dataset used is `8. Netflix Dataset.csv` (source: likely Kaggle). It contains information about movies and TV shows, including:
- `Show_Id`: unique identifier
- `Category`: Movie or TV Show
- `Title`: title of the content
- `Director`: director(s) of the content
- `Cast`: cast members
- `Country`: country of production
- `Release_Date`: date when the content was added to Netflix
- `Rating`: content rating (e.g., PG-13, TV-MA)
- `Duration`: runtime (minutes for movies, number of seasons for TV shows)
- `Type`: genre(s)
- `Description`: brief summary

## Requirements

The following Python libraries are required:
- pandas
- numpy
- matplotlib
- seaborn

You can install them using pip:
```bash
pip install pandas numpy matplotlib seaborn

## License
This project is intended for educational purposes. The dataset used is publicly available on Kaggle and is subject to its original license. Feel free to use the code for learning and experimentation.
