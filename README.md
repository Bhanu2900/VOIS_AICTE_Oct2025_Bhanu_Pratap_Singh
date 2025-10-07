# VOIS_AICTE_Oct2025_Bhanu_Pratap_Singh
Airbnb NYC Lodging Market Analysis
📝 Project Description
This project involves an in-depth research analysis of the New York City Airbnb dataset to extract meaningful insights and illuminate the dynamics of the city's lodging market. Utilizing rigorous data cleaning, exploratory analysis, and visualization techniques, the study aims to discern factors influencing listing availability, pricing strategies, and overall customer satisfaction. This analysis is crucial for understanding Airbnb's operations in a major urban environment.

🎯 Target Audience
The primary insights from this analysis are designed to assist various stakeholders in navigating the short-term accommodation landscape:

Airbnb Hosts: To optimize pricing, improve service quality, and increase the availability of their listings.

Airbnb Management/Stakeholders: To inform business strategies, refine commission models, and understand market trends.

Urban Planners & Regulators: To assess the market's impact and inform local housing policies.

🛠️ Technology Stack
The analysis and visualizations were performed entirely within a Google Colab environment using the Python programming language and the following libraries:

Category	Library	Purpose
Data Handling	Pandas	Data structure manipulation and cleaning.
Statistical Visualization	Seaborn (sns)	High-level interface for drawing attractive and informative statistical graphics (Box plots, Regression plots, Bar plots).
General Plotting	Matplotlib (plt)	Low-level plotting functions (setting labels, titles, and figure sizes).
📈 Key Areas of Analysis
The analysis focused on answering key business questions about the relationships between listing characteristics, host performance, and financial metrics:

Host Verification & Review Rate:

Comparison of the Average Review Rate across different Host Verification Statuses (visualized using bar plots and box plots).

Price and Service Fee Correlation:

Calculation of the correlation between a listing's price_$ and its service_fee_$.

Finding: The analysis showed an extremely high positive correlation (~0.999), visualized using a Regression Plot.

Review Rate by Location and Property Type:

Examination of the Average Review Rate for each Room/Property Type within various Neighbourhood Groups (visualized using a grouped bar plot).

Host Listings Count vs. Availability:

Investigation into whether hosts with a higher calculated host listings count are more likely to maintain higher availability 365.

The relationship was visualized using a Regression Plot.

🏃 Getting Started
This project is hosted on Google Colab, making it simple to run.

Click on the following notebook link:
Analysis Notebook

Select "Runtime" from the top menu.

Select "Run all" to execute all cells, including data import, cleaning, and visualization steps.

