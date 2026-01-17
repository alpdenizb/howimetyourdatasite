# IE 421 - US Flight Data Analysis

## Team Members-How I Met Your Data
* Alp Deniz Batuhan (123203096)
* Emir Buğra Çakır (123203102)
* Beste Eren (122203049)
* Tuana Şen (122203052)

## Data
The analysis is based on the **2015 U.S. Flight Delays and Cancellations** dataset.
* **Source:** [Kaggle - 2015 Flight Delays and Cancellations](https://www.kaggle.com/datasets/usdot/flight-delays)
* **Dataset Size:** Contains over 5.8 million flight records (approx. 600MB).
* **Access & Storage:** Due to the large file size, the dataset is managed and uploaded using **Git LFS (Large File Storage)** to ensure version control and repository efficiency. Additionally, the project scripts utilize the **kagglehub** library for seamless data acquisition and management during the analysis.

## Research Questions
Our project investigates three primary research questions:

1. **RQ1 - The "Snowball Effect":** We examine how minor disruptions early in a flight's daily rotation compound and escalate into significant delays by the end of the day.
2. 2. **RQ2 - Temporal Bottlenecks and Monthly Congestion:** This analysis identifies critical operational bottlenecks through a dual-visualization strategy. A **static jointplot** utilizes hexagonal binning to map flight density across days and hours, pinpointing specific "rush hour" windows. This is further enriched by an **interactive bin plot** (dashboard) that monitors monthly congestion patterns across 10 major airline hubs, signaling when flight volumes surpass safety thresholds. By combining high-resolution daily mapping with broad monthly trends, this approach enables more flexible scheduling and data-driven resource allocation.
3. **RQ3 - Arrival Delay Prediction:** We analyze the impact of departure delays, taxi-out times, and flight distances on final arrival punctuality to quantify how delays at the gate translate to the final arrival time.

## Our Models
We utilized both descriptive and predictive modeling techniques to extract insights:
* **Descriptive Models:** **Hexagonal Binning (Jointplots)** and **Heatmap** analyses were implemented to visualize operational intensity and the propagation of the "Snowball Effect."
* **Predictive Model:** A **Multiple Linear Regression (OLS)** model was constructed to forecast arrival delays. Our model achieved a high **R-squared value of 0.926**, demonstrating strong predictive power regarding schedule deviations.

## Website link
You can explore our interactive dashboards, detailed visualizations, and final project conclusions through our live website:

👉 [**Interactive Project Dashboard**](https://yourusername.github.io/your-repository-name/)
