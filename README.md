## Olympic Data Analysis System
The Olympic Data Analysis System is an interactive data analytics application developed using Python, FastAPI, and Streamlit. It provides comprehensive insights into Olympic history using the Kaggle Olympic datasets (athlete_events and noc_regions). The system enables users to explore medal statistics, athlete performance, and country-wise trends through dynamic visualizations and structured analysis.

The application offers a sidebar-driven interface where users can select different analytical views, including Medal Tally, Overall Analysis, Country-wise Analysis, and Athlete-wise Analysis. Each section presents data in a structured and visually intuitive format to support deep exploration of Olympic trends.


## Features
Medal Tally Analysis:
- Year-wise, country-wise, and overall medal tallies
- Filter options including year-overall, country-year, and year-country views
- Structured tabular representation for clear comparison

Overall Analysis:
- Key statistics such as number of editions, host cities, sports, events, nations, and athletes
- Trend analysis of participating nations, events, and athletes over time
- Heatmap showing number of events per sport across Olympic editions
- Identification of the most successful athletes overall or by selected sport (top 10)

Country-Wise Analysis:
- Medal tally trends for selected countries over the years
- Sport-wise performance heatmaps for each country
- Top 10 athletes list for the selected country

Athlete-Wise Analysis:
- Age distribution by medal type (gold, silver, bronze, overall)
- Age distribution with respect to sports for gold medalists
- Height vs weight analysis (overall and sport-specific)
- Male vs female participation trends with interactive line selection


## Tech Stack
- Python
- FastAPI (Backend API)
- Streamlit (Frontend Visualization)
- Pandas, NumPy
- Matplotlib, Seaborn, Plotly
- Scipy and data preprocessing utilities
- Kaggle Olympic Datasets (athlete_events, noc_regions)


## How It Works
1. Olympic datasets are cleaned, merged, and preprocessed for analysis.
2. Users select analysis type through sidebar controls.
3. Statistical computations and visualizations are generated dynamically.
4. Interactive charts, heatmaps, and tables provide deep analytical insights.


## Conclusion
The Olympic Data Analysis System successfully transforms complex historical Olympic datasets into meaningful insights through interactive analytics and visual storytelling. By combining a FastAPI-powered backend with a Streamlit-based frontend, the application delivers a responsive, scalable, and user-friendly experience. The structured analytical sections—ranging from medal tallies to athlete demographics—enable users to explore trends at multiple levels of detail. This project demonstrates strong capabilities in data preprocessing, statistical analysis, visualization, and full-stack Python development, making it a robust solution for sports analytics and data-driven exploration.




