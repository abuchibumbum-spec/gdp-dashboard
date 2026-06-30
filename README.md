# GDP Dashboard

An interactive Streamlit dashboard for exploring World Bank GDP data across countries and years, with growth comparisons and time-series visualization.

## Features

- **Year range slider** to filter the time period of interest
- **Country multiselect** to compare GDP across multiple countries at once
- **Line chart** showing GDP trends over time, colored by country
- **Growth metrics** showing each selected country's latest GDP and growth multiple relative to the start of the selected range
- **Cached data loading** for fast interaction after the initial load

## Getting Started

### Requirements
- Python 3.9+

### Installation
```bash
git clone https://github.com/abuchibumbum-spec/gdp-dashboard.git
cd gdp-dashboard
pip install -r requirements.txt
```

### Run
```bash
streamlit run app.py
```
This opens the dashboard in your browser, usually at `http://localhost:8501`.

## Data Source

GDP data is sourced from the [World Bank Open Data](https://data.worldbank.org/) project, covering 1960–2022. Some country/year combinations have missing values.

## License

Feel free to use and adapt this project.
