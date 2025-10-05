EcoForecast

EcoForecast is a data-driven system for analyzing and forecasting climate change patterns using global datasets from NASA and other sources. The project applies machine learning and advanced data visualization techniques to model temperature variations, carbon emissions, sea-level rise, and global risk indices, enabling better understanding of climate risks and future environmental impacts.

Features
-------------------
Data Cleaning & Preprocessing:
Handles missing values, removes unnecessary columns, and ensures datasets are ready for analysis.

Datasets Used
-------------------
Annual Surface Temperature Change (2001–2022)

Carbon Emissions (2003–2021)

Sea Level Rise (2000–2021)

World Risk Index (2011–2021)

Data Visualization
---------------------
Heatmaps for each dataset using Seaborn and Matplotlib

Helps identify trends, anomalies, and correlations across countries and years

Machine Learning Model
-------------------------
Uses Linear Regression to predict climate-related metrics

Evaluates performance with Mean Squared Error (MSE)

Integration of Multiple Datasets
------------------------------------
Combines temperature, sea-level, emissions, and risk indices to build a comprehensive climate model

Technologies & Tools
--------------------------
Python (Pandas, NumPy, Scikit-learn)

Seaborn & Matplotlib for visualization

Google Colab for development

Excel & CSV datasets

How to Run
----------------
Clone the repository:

git clone https://github.com/your-username/eco-forecast.git
cd eco-forecast


Install dependencies:

pip install pandas numpy seaborn matplotlib scikit-learn xlrd openpyxl


Mount Google Drive in Colab (if using Colab) and set dataset paths:

from google.colab import drive
drive.mount('/content/drive')

Run the notebook EcoForecast.py to preprocess data, generate heatmaps, and train the model.

Project Outcomes
-----------------------
Visualized global climate change patterns using interactive heatmaps.

Developed predictive models to estimate climate metrics across countries.

Provided actionable insights into environmental risk factors and trends.
