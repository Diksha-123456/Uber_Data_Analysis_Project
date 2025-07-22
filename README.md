# Uber_Data_Analysis_Project

Project Description:
The Uber Data Analysis project focuses on analyzing ride request data to identify operational inefficiencies in Uber’s transportation network. By studying rider and driver behavior patterns, the project provides valuable insights into problems such as driver unavailability, trip cancellations, and temporal demand-supply mismatches.The analysis is based on a real-world dataset of Uber ride requests. It aims to answer questions like:

When is the demand for rides highest?

Where do cancellations mostly occur?

What time and location have the highest gap between demand and supply?

This project uses Python-based data analytics and visualization tools to explore these questions and offer strategic recommendations for improving service quality and customer satisfaction.

Key Features of the Uber Data Analysis Project:

1. Data Cleaning & Preprocessing
Converted timestamps into proper datetime format.

Handled missing values and inconsistent data.

Derived new fields like request hour, date, and time slots for deeper analysis.

2. Exploratory Data Analysis (EDA)
Visualized the distribution of ride requests across hours of the day.

Analyzed patterns in request status (Trip Completed, Cancelled, No Cars Available).

Segregated analysis by pickup points: Airport and City.

3. Time Slot Classification
Categorized ride requests into custom time slots:

Early Morning (12 AM – 4 AM)

Morning Rush (5 AM – 9 AM)

Day Time (10 AM – 4 PM)

Evening Rush (5 PM – 9 PM)

Late Night (10 PM – 11 PM)

4. Demand vs Supply Gap Analysis
Compared the number of requests with completed trips.

Identified peak hours with high demand but low availability.

Highlighted mismatch in driver allocation, especially at specific pickup points.

5. Cancellation and Unavailability Analysis
Visualized and interpreted causes of ride request failures.

Found high cancellation rates during morning hours from the city.

Noted frequent "No Cars Available" status at the airport in the evening.

6. Business Insights & Recommendations
Suggested reallocation of driver resources.

Proposed bonus systems to encourage off-peak availability.

Recommended implementation of a ride pre-scheduling feature.

📈 Technologies & Tools Used:
Python (Core language)

Jupyter Notebook (Interactive coding)

Pandas (Data manipulation)

NumPy (Numerical operations)

Matplotlib & Seaborn (Data visualization)

CSV File Input (UberDataset.csv)
