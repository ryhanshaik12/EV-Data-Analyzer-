# EV-Data-Analyzer-
A beginner-friendly Python data analysis project that explores electric vehicle (EV) specifications using Pandas and Matplotlib. The project analyzes driving range, top speed, fast-charging power, and battery capacity to help compare electric vehicles through statistics and visualizations.

## 📌 Project Overview

Electric vehicles have different performance characteristics, including driving range, battery capacity, top speed, and charging power.

This project uses a CSV dataset of electric vehicle specifications to summarize these characteristics, identify vehicles with the highest values in selected categories, and visualize the relationship between battery capacity and driving range.

## ✨ Features

- Loads electric vehicle data from a CSV file.
- Displays the total number of vehicle records.
- Counts the number of distinct vehicle brands.
- Calculates average driving range.
- Calculates average top speed.
- Calculates average energy consumption.
- Identifies the top 10 vehicles by driving range.
- Identifies the top 10 vehicles by top speed.
- Identifies the top 10 vehicles by fast-charging power.
- Creates a dashboard containing four charts.

## 📊 Visualizations

The dashboard includes the following charts:

1. **Top 10 EVs by Driving Range** — compares the listed driving ranges of the top 10 vehicles.
2. **Top 10 EVs by Top Speed** — compares the listed maximum speeds of the top 10 vehicles.
3. **Top 10 EVs by Fast-Charging Power** — compares the listed DC fast-charging power values.
4. **Battery Capacity vs. Driving Range** — uses a scatter plot to explore the relationship between battery capacity and driving range.

## 🛠️ Technologies Used

- **Python** — programming language used to build the project.
- **Pandas** — loads, organizes, and analyzes tabular data.
- **Matplotlib** — creates the charts and dashboard.
- **Pathlib** — locates the dataset in the project folder.

## 📁 Project Structure

```text
EV-Data-Explorer/
│
├── app.py
├── electric_vehicles_spec_2025.csv
└── README.md
```

## 📂 Dataset

This project uses the **Electric Vehicle Specs Dataset 2025**, published by UrvishAhir1 on Hugging Face.

**Dataset link:**  
https://huggingface.co/datasets/UrvishAhir1/Electric-Vehicle-Specs-Dataset-2025

The dataset contains electric vehicle specifications used for the analysis.

The project uses columns such as:

- `brand`
- `model`
- `range_km`
- `top_speed_kmh`
- `efficiency_wh_per_km`
- `battery_capacity_kWh`
- `fast_charging_power_kw_dc`

Refer to the original dataset page for the license and attribution requirements.

## ⚙️ Installation and Setup

### 1. Install Python

Download and install Python from:

https://www.python.org/downloads/

### 2. Install the required libraries

Open Command Prompt in your project folder and run:

```bash
python -m pip install pandas matplotlib
```

### 3. Prepare the dataset

Place `electric_vehicles_spec_2025.csv` in the same folder as `app.py`.

### 4. Run the project

Open Command Prompt and navigate to the project folder:

```bash
cd path\to\EV-Data-Explorer
```

Run the Python application:

```bash
python app.py
```

The program prints summary statistics and the top 10 vehicles in three categories. It then opens a window displaying the four charts.

## 🧠 Concepts Demonstrated

This project demonstrates introductory Python data analysis concepts, including:

- Reading CSV files with Pandas.
- Working with rows and columns in a DataFrame.
- Handling missing model names.
- Counting distinct values.
- Calculating averages.
- Sorting data to identify the largest values.
- Creating bar charts and scatter plots.

## ⚠️ Limitations

- Results depend on the accuracy and completeness of the source dataset.
- Listed specifications may differ from real-world driving and charging performance.
- The top 10 rankings depend on the values recorded in the dataset.
- The scatter plot shows a relationship between battery capacity and range; it does not establish causation.
- The program assumes the expected column names are present in the CSV file.

## 🚀 Future Improvements

Potential improvements include:

- Add data validation and handling for missing or invalid numerical values.
- Allow users to filter vehicles by manufacturer or body type.
- Add comparisons of vehicle efficiency and battery capacity.
- Build an interactive dashboard using Streamlit.
- Add a project screenshot to the README.

A beginner Python data analysis project created to explore electric vehicle specifications and develop practical data analysis and visualization skills.
