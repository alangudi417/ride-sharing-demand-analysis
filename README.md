# Zuber Ride-Sharing Market & Demand Analysis

## 📊 Project Overview
This project analyzes ride-sharing data from Zuber, a new mobility company launching operations in Chicago. The objective is to understand passenger demand patterns, evaluate the competitive landscape, and determine how external factors such as weather influence ride frequency and trip duration.
Using trip records, weather data, and competitor benchmarking datasets, the analysis transforms raw operational data into actionable business insights. The findings support strategic planning, driver allocation decisions, and operational optimization for Zuber’s market entry.

## 📊 Dataset Description
The analysis integrates multiple datasets representing different aspects of ride-sharing operations:
- Trip Records – Ride details including pickup/dropoff locations and trip durations
- Neighborhood Data – Aggregated trip counts by Chicago neighborhoods
- Competitor Data – Trip volume information from existing taxi and ride-sharing companies
- Weather Data – Weather conditions affecting trip duration and demand
These datasets were cleaned, validated, and merged to create a unified analytical framework

## ⚙️ Methodology
The project follows a structured data analytics workflow:
1. Data Preprocessing
    - Cleaned and validated multiple datasets
    - Corrected data types and handled missing values
    - Standardized geographic and time-based features
    - Prepared datasets for merging and analysis

2. Exploratory Data Analysis (EDA)
    - Analyzed trip distribution across Chicago neighborhoods
    - Identified high-demand dropoff locations
    - Compared ride volumes across competing companies
    - Visualized passenger demand trends and service concentration

3. Statistical Hypothesis Testing
    - Conducted a Student’s t-test to evaluate whether rainy weather impacts trip duration between the Loop and O’Hare International Airport on Saturdays
    - Tested statistical significance of weather-related travel behavior changes

## 📈 Project Highlights
- Integrated multi-source transportation and weather datasets
- Identified geographic demand hotspots using ride frequency analysis
- Evaluated competitive market positioning using benchmark trip data
- Applied statistical testing to validate operational assumptions
- Generated data-driven strategic recommendations

## 📈 Results
Key Findings
Passenger Preferences and Demand Concentration
- The Loop is the primary ride-sharing hub, averaging approximately 10,727 trips
- Other high-demand neighborhoods include:
    - River North (9,523 trips)
    - Streeterville (6,664 trips)
    - West Loop (5,163 trips)
These areas represent the highest concentration of passenger activity and key operational targets.

Competitive Landscape
- Flash Cab dominates the market with 19,558 trips
- Taxi Affiliation Services ranks second with 11,422 trips
- The market shows strong incumbent competitors, highlighting the need for competitive differentiation.

Impact of Weather on Ride Duration
- Statistical testing produced a p-value < 0.05
- The null hypothesis was rejected
- Rain significantly increases trip duration between the Loop and O’Hare Airport

💼 Strategic Business Insight
While passenger demand is heavily concentrated in downtown Chicago, external factors such as weather significantly affect operational performance. Zuber must account for both geographic demand and environmental conditions when designing service strategies.

Strategic Recommendations
1. Geographic Targeting
    - Prioritize driver deployment and marketing campaigns in:
        - The Loop
        - River North
        - Streeterville
        - West Loop

2. Weather-Based Operational Adjustments
    - Integrate weather data into:
        - ETA prediction algorithms
        - Surge pricing models
        - Driver scheduling strategies

3. Competitive Strategy
    - Analyze Flash Cab’s operational structure
    - Develop competitive pricing or differentiated service offerings
    - Focus on high-demand zones to accelerate market penetration

▶️ How to Run the Project
1.	Clone this repository: git clone https://github.com/alangudi417/ride-sharing-demand-analysis.git Navigate to the project folder: cd ride-sharing-demand-analysis
2.	Create and activate virtual environment: python -m venv venv venv\Scripts\activate # Windows source venv/bin/activate # Mac/Linux
3.	Install dependencies: pip install -r requirements.txt
4.	Launch Jupyter Notebook: jupyter notebook
5.	Open notebooks/ride_sharing_analysis.ipynb