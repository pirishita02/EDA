🍽️ Zomato Restaurant Data - Exploratory Data Analysis (EDA)

📌 Project Overview
This project performs a detailed Exploratory Data Analysis (EDA) on Zomato’s restaurant data to uncover insights about restaurant locations, cuisines, ratings, costs, and delivery services. 
The analysis uses Python libraries such as pandas, matplotlib, and seaborn to clean, explore, and visualize the data effectively.
The aim is to understand patterns in customer ratings, pricing strategies, cuisine popularity, and the geographic distribution of services like online delivery and table booking.

📊 Dataset Information
The dataset used is the Zomato Restaurants Dataset, which contains data for 9551 restaurants across multiple countries. Each row provides information about a restaurant including:
Restaurant name, location (city, locality)
Cuisines served
Average cost for two people
Rating and number of votes
Availability of online delivery and table booking
Geographic coordinates (latitude, longitude)

🔍 EDA Objectives
Understand the structure and quality of the dataset
Identify missing or inconsistent data
Analyze restaurant distribution across cities and countries
Examine the relationship between cost, rating, and votes
Visualize delivery and table booking availability
Highlight top cuisines and their performance
Generate correlation insights among numeric features

🛠️ Tools & Libraries Used
Python (3.x)
Pandas – data manipulation and cleaning
Seaborn and Matplotlib – data visualization
Jupyter Notebook – interactive data exploration

📈 Key Visualizations & Insights
Histograms of votes and average cost to observe skewness
Box plots to detect outliers in cost and ratings across cities
Bar plots comparing average ratings by city and by delivery availability
Heatmap of correlation between numerical variables
Count plots showing frequency distribution of ratings, cuisines, etc.

✅ Key Findings
Most restaurants are concentrated in Indian cities, with New Delhi being the most represented.
North Indian cuisine is the most commonly served type.
Restaurants with table booking and online delivery generally have slightly better average ratings.
Ratings tend to be biased toward positive values; very few restaurants have ratings below 2.
Votes and aggregate ratings are moderately correlated, indicating popularity contributes to better ratings.

📁 Project Structure
├── EDA.ipynb              # Jupyter notebook with complete EDA code
├── zomato.csv             # Dataset file
├── README.md              # Project description (this file)

📬 Future Enhancements
Convert the analysis into a web dashboard using Plotly Dash or Streamlit
Apply clustering to group similar restaurants based on rating, cost, and cuisine
Perform predictive modeling on restaurant success (e.g., rating prediction)

🙌 Acknowledgement
Dataset sourced from Zomato, available publicly for educational and analytical purposes.
