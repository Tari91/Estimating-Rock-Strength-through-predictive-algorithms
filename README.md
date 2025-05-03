🪨 **Rock Strength Estimation**
This project delivers a robust, scalable, and extensible pipeline for estimating Rock Strength using advanced machine learning models and synthetic geotechnical data. It is ideal for geotechnical engineers, researchers, and students interested in data-driven modeling of rock properties.

📦 Project Contents
File	Description
synthetic_rock_strength_data.xlsx	Excel file with synthetic geotechnical features and rock strength values
rock_strength_estimation.py	Python script for data generation, model training, and evaluation
README.md	Documentation and usage instructions

📊 **Features**
Synthetic Data Generation: Includes realistic geotechnical parameters like porosity, density, water content, etc.

Machine Learning Pipeline: Implements Random Forest Regression with performance metrics.

Export Functionality: Saves datasets in .xlsx format for easy analysis and sharing.

Visualization: Produces scatter plots to compare actual vs predicted values.

Modular Design: Easily extend to support real datasets or alternative models (XGBoost, MLP, etc.).

🧪 Dataset Structure
Feature	Description	Unit
Porosity	Void fraction in the rock	%
Density	Rock density	g/cm³
Grain Size	Average particle diameter	mm
Water Content	Moisture level	%
Depth	Depth from the surface	meters
Cementation Index	Degree of bonding in the material	unitless
Rock Strength	Simulated UCS (target variable)	MPa

🛠 Installation
Ensure Python 3.7+ is installed. Then, install required packages:

bash
Copy
Edit
pip install -r requirements.txt
requirements.txt

nginx
Copy
Edit
pandas
numpy
scikit-learn
matplotlib
seaborn
openpyxl
🚀 Usage
Run the pipeline with:

bash
Copy
Edit
python rock_strength_estimation.py
This will:

Generate 1000 rows of synthetic data

Train a Random Forest Regressor

Evaluate and visualize model performance

Export the dataset to synthetic_rock_strength_data.xlsx

🔄 Extending the Model
To upgrade the pipeline:

Swap RandomForestRegressor with models like XGBRegressor, SVR, or MLPRegressor

Integrate with GridSearchCV for hyperparameter tuning

Replace synthetic data with real field or lab results

🧠 Example Use Cases
Teaching geotechnical data modeling

Prototyping rock strength prediction tools

Comparing regression techniques for geological parameters

🧾 Version
Version: 1.0.0
Last Updated: May 2025

👤 Author
Tarinabo williamtarinabo@gmail.com
