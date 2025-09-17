# Olympic Data Analysis

An interactive web application for exploratory data analysis (EDA) of over a century of Olympic history. This project dives into trends in participation, performance, and progression across nations, sports, and athletes using Summer Olympic data.

## Features

- **Medal Tally**: View overall medal counts, filter by year or country, and analyze specific performances.
- **Overall Analysis**: Explore key statistics like number of editions, hosting cities, sports, events, athletes, and nations. Visualize data over time with interactive charts.
- **Country-wise Analysis**: Analyze a country's medal tally over years, sports performance heatmaps, and top athletes.
- **Athlete-wise Analysis**: Distribution of ages by medal type, height vs. weight scatter plots, and gender participation trends over time.

## Technologies Used

- **Python**: Core programming language.
- **Streamlit**: Framework for building the interactive web app.
- **Pandas**: Data manipulation and analysis.
- **NumPy**: Numerical computations.
- **Plotly**: Interactive visualizations (express and figure_factory).
- **Seaborn** and **Matplotlib**: Additional plotting for heatmaps and scatter plots.

## Installation

1. **Clone the Repository**:
   ```
   git clone https://github.com/your-username/olympic-data-analysis.git
   cd olympic-data-analysis
   ```

2. **Create a Virtual Environment** (recommended):
   ```
   python -m venv venv
   # On Windows: venv\Scripts\activate
   # On macOS/Linux: source venv/bin/activate
   ```

3. **Install Dependencies**:
   ```
   pip install -r requirements.txt
   ```
   If `requirements.txt` doesn't exist, install the following manually:
   ```
   pip install streamlit pandas numpy plotly seaborn matplotlib
   ```

4. **Data Files**:
   - Place `athlete_events.csv` and `noc_regions.csv` in the project directory.
   - These datasets contain historical Olympic athlete and event data.

## Usage

1. **Activate the Virtual Environment** (if created):
   ```
   # On Windows: venv\Scripts\activate
   # On macOS/Linux: source venv/bin/activate
   ```

2. **Run the Application**:
   ```
   streamlit run app.py
   ```

3. Open your browser to `http://localhost:8501` to interact with the app.

4. Use the sidebar to select analysis options and explore the data through interactive charts and tables.

## Project Structure

- `app.py`: Main Streamlit application file.
- `helper.py`: Utility functions for data processing and visualization preparation.
- `preprocessor.py`: Data preprocessing functions.
- `analysis.ipynb`: Jupyter notebook for initial EDA and data exploration.
- `README.md`: Project documentation.

## Data Sources

- `athlete_events.csv`: Contains athlete details, events, medals, etc.
- `noc_regions.csv`: Maps NOC codes to regions/countries.

These datasets are typically sourced from public Olympic data repositories or Kaggle.

## Contributing

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature-name`
3. Commit changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature-name`
5. Open a pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Inspired by Olympic data analysis tutorials and Kaggle datasets.
- Icons and images sourced from public domains.