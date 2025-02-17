# Global Air Quality Analysis Program

This program analyzes and visualizes air quality data from various countries based on the dataset from Kaggle. It provides insights into air quality, temperature, and other relevant environmental factors.

## Dataset Source
The dataset used for this program is sourced from [Kaggle - Global Weather Repository](https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/data).

### Dataset Description
The `GlobalWeatherRepository.csv` file contains the following columns:
1. **country**: Country of the weather data.
2. **location_name**: Name of the location (city).
3. **latitude**: Latitude coordinate of the location.
4. **longitude**: Longitude coordinate of the location.
5. **timezone**: Timezone of the location.
6. **last_updated_epoch**: Unix timestamp of the last data update.
7. **last_updated**: Local time of the last data update.
8. **temperature_celsius**: Temperature in degrees Celsius.
9. **temperature_fahrenheit**: Temperature in degrees Fahrenheit.
10. **condition_text**: Weather condition description.
11. **air_quality_index**: Air quality index of the location (if available).

### Features
- Data exploration and visualization of air quality by country and location.
- Filtering and analyzing data based on user-specified parameters such as temperature, condition, or AQI range.
- Insights into the relationship between weather conditions and air quality.

### Requirements
To run this program, ensure you have the following installed:
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook (optional, for notebook execution)

### Installation
1. Clone this repository.
   ```bash
   git clone <repository-url>
   cd <repository-folder>
2. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
### Usage
1. Place the GlobalWeatherRepository.csv file in the root directory of the project.
2. Run the notebook using Jupyter:
    ```bash
    jupyter notebook main.ipynb
3. Follow the steps in the notebook to explore and analyze the data.
### Visualizations and Analysis
The program includes several visualizations, such as:

- Bar charts comparing AQI across countries.
- Scatter plots showing temperature versus AQI.
- Heatmaps to identify regions with poor air quality.
### Contributions
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

### License
This project is licensed under the MIT License. See the LICENSE file for details.

### Author
Developed by Natanael Geraldo Sulaiman.