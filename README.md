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

1. **RQ1 - The "Snowball Effect":** This analysis investigates the "Snowball Effect," demonstrating how flight delays compound as an aircraft completes multiple segments throughout its daily rotation. We quantify how early-day disruptions escalate into significant cumulative delays by the end of the schedule.

2. **RQ2 - Temporal Bottlenecks and Monthly Congestion:** This study identifies operational bottlenecks, integrating a static jointplot for daily rush-hour mapping and an interactive bin plot for monthly hub monitoring. While the jointplot utilizes hexagonal binning to pinpoint high-density traffic windows, the interactive dashboard tracks when flight volumes surpass safety thresholds across 10 major airports.

3. **RQ3 - Arrival Delay Prediction:** Utilizing a Multiple Linear Regression (OLS) model, this analysis quantifies the impact of departure delays, taxi-out times, and flight distances on arrival punctuality. Achieving a high R-squared value of 0.926, the model demonstrates that arrival delays are highly predictable based on early-stage departure metrics, with departure delay serving as the strongest indicator of the final arrival time.

## Our Models
We utilized both descriptive and predictive modeling techniques to extract insights:
* **Descriptive Models:** **Hexagonal Binning (Jointplots)** and **Heatmap** analyses were implemented to visualize operational intensity and the propagation of the "Snowball Effect."
* **Predictive Model:** A **Multiple Linear Regression (OLS)** model was constructed to forecast arrival delays. Our model achieved a high **R-squared value of 0.926**, demonstrating strong predictive power regarding schedule deviations.

## Website link
You can explore our interactive dashboards, detailed visualizations, and final project conclusions through our live website:

👉 [**Interactive Project Dashboard**](https://yourusername.github.io/your-repository-name/)
