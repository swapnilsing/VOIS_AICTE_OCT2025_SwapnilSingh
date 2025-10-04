# VOIS_INTERNSHIP_PROJECT
Airbnb Price Prediction & Booking Analysis
This project uses machine learning to predict Airbnb listing prices in New York City. By analyzing a wide range of features from historical listing data, the model aims to provide a data-driven pricing tool for hosts and a fair pricing reference for travelers.

📝 Problem Statement
Setting the right price is one of the biggest challenges for Airbnb hosts. The market is dynamic and pricing is influenced by a multitude of factors. This project addresses the core issues hosts face:

Complex Pricing Decisions: Hosts face the difficult task of pricing their listings correctly due to numerous variables like location, seasonality, amenities, and local events.

Lack of Data-Driven Tools: Most hosts rely on manual comparisons and guesswork, as there is a significant absence of accessible, data-driven pricing tools.

Risk of Suboptimal Pricing: This manual approach frequently leads to pricing that is either too high (resulting in low occupancy) or too low (resulting in lost revenue).

Inefficient and Time-Consuming: Manually tracking competitors and market trends is an inefficient process, especially for hosts managing multiple properties.

Direct Impact on Revenue: Ultimately, this pricing inefficiency translates into a significant loss of potential income and hinders a host's success.

🎯 Project Goals & End Users
The goal is to develop a regression model that provides accurate and dynamic pricing recommendations. The intended end users include:

Airbnb Hosts: To optimize listing prices, maximize revenue, and stay competitive.

Travelers: To evaluate whether a listing is fairly priced based on its features and location.

Airbnb Platform Analysts: To gain insights for improving automated pricing suggestions and platform trust.

Researchers/Students: To study the impact of various features on the rental housing market.

🛠️ Technologies Used
This project is built using a standard Python data science stack:

Core Language: Python

Data Manipulation: Pandas & NumPy

Machine Learning: Scikit-learn (for model training, regression, and evaluation)

Data Visualization: Matplotlib & Seaborn

Development Environment: Google Colab / Jupyter Notebook

File Handling: Openpyxl and built-in CSV libraries

💾 Dataset
The analysis is based on a dataset of Airbnb listings from New York City.

("C:\Users\Supre\Downloads\VOIS _INTERSHIP\1730285881-Airbnb_Open_Data.xlsx")

The dataset includes features such as neighborhood, property type, room type, number of bedrooms/bathrooms, price, guest reviews, and availability.

⚙️ Setup and Installation
To run this project locally, follow these steps:

Clone the repository:

Bash

git clone https://github.com/your-username/airbnb-price-prediction.git
cd airbnb-price-prediction
Create a virtual environment:

Bash

python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
Install the required dependencies:

Bash

pip install -r requirements.txt
(Note: If you don't have a requirements.txt file, you can create one by running pip freeze > requirements.txt after installing the libraries listed above.)

🚀 Usage
The primary analysis and model training can be found in the Jupyter Notebook.

Start Jupyter Notebook:

Bash

jupyter notebook
Open the Airbnb_Analysis.ipynb (or similarly named) notebook to see the code for data cleaning, exploratory data analysis (EDA), model training, and evaluation.

