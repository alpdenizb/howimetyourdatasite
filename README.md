# IE 421 - US Flight Data Analysis

This project analyzes operational inefficiencies, delay propagation, and air traffic congestion within the aviation sector using US flight data from 2015.

## Team Members
* **Group Name:** How I Met Your Data
* [Member Name 1]
* [Member Name 2]
* [Member Name 3]

## Data
The analysis is based on the **2015 U.S. Flight Delays and Cancellations** dataset.
* **Dataset Size:** Contains over 5.8 million flight records (approx. 600MB).
* **Access Method:** Due to GitHub's file size limitations, the `Data/` folder contains only a **sample version** (100 rows) of the dataset. However, the project scripts (`Scripts/`) are designed to automatically fetch the full dataset via the `kagglehub` library during execution to ensure a complete and accurate analysis.

## Research Questions
Our project investigates three primary research questions:

1. **RQ1 - The "Snowball Effect":** We examine how minor disruptions early in a flight's daily rotation compound and escalate into significant delays by the end of the day, specifically focusing on the 30-90 minute delay interval.
2. **RQ2 - Peak Hour Bottlenecks:** We identify critical operational bottlenecks by mapping flight density across different days of the week and specific time windows using hexagonal binning.
3. **RQ3 - Arrival Delay Prediction:** We analyze the impact of departure delays, taxi-out times, and flight distances on final arrival punctuality to quantify how delays at the gate translate to the final arrival time.

## Our Models
We utilized both descriptive and predictive modeling techniques to extract insights:
* **Descriptive Models:** **Hexagonal Binning (Jointplots)** and **Heatmap** analyses were implemented to visualize operational intensity and the propagation of the "Snowball Effect."
* **Predictive Model:** A **Multiple Linear Regression (OLS)** model was constructed to forecast arrival delays. Our model achieved a high **R-squared value of 0.926**, demonstrating strong predictive power regarding schedule deviations.

## Website link
You can explore our interactive dashboards, detailed visualizations, and final project conclusions through our live website:

👉 [**Interactive Project Dashboard**](https://yourusername.github.io/your-repository-name/)
