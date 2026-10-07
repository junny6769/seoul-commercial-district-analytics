# Seoul Commercial District Analytics Platform

A Streamlit analytics platform developed for the Snowflake AI & Data Hackathon to compare Seoul commercial districts and generate industry-specific location recommendations using Snowflake datasets and SQL-based analysis.

## Overview

The project combines commercial and demographic data to help users evaluate Seoul districts for different business categories.

The analysis uses data including:

- Card sales
- Floating population
- Income
- Asset data
- Commercial district information

Users can compare districts through an interactive Streamlit interface and receive rankings based on industry-specific criteria.

## Key Features

- Interactive district comparison through Streamlit
- SQL-based ranking of Seoul commercial districts
- Analysis of card sales, population, income and asset data
- Industry-specific location recommendations
- AI-generated recommendations using Cortex AI
- Data preprocessing and transformation using Python
- Snowflake as the central data platform

## Tech Stack

- **Snowflake** — data storage and querying
- **SQL** — district ranking and analytical logic
- **Python** — preprocessing and application logic
- **Streamlit** — interactive analytics platform
- **Git/GitHub** — version control and collaboration

## How It Works

1. Snowflake datasets are prepared and transformed for analysis.
2. Commercial districts are compared across relevant indicators.
3. SQL-based ranking logic evaluates districts based on the selected business category.
4. Results are displayed through the Streamlit application.
5. Users can explore and compare recommended commercial areas.

## Project Structure

```text
seoul-commercial-district-analytics/
├── pages/              # Streamlit application pages
├── preprocessing/      # Data preparation and transformation
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
└── README.md
```

## Team

## Team

Developed as part of a four-person engineering–business team during the Snowflake AI & Data Hackathon.

My contribution focused on the engineering and analytics side, including data preprocessing, SQL-based ranking logic and development of the Streamlit platform.

**Hyo Won Ahn** worked on the AI recommendation component, using Cortex AI to generate additional insights and recommendations from the analytical results.

The business-side team members contributed to problem definition, business requirements and interpretation of the recommendations.

## What I Learned

This project strengthened my experience in:

- Working with Snowflake datasets
- Building SQL-based analytical logic
- Developing interactive applications with Streamlit
- Translating business requirements into analytical features
- Collaborating across engineering and business roles

## Limitations

The Streamlit application is currently unavailable because the project relied on API access provided specifically during the hackathon period. That access has since expired, so the live site is not currently functional.

The repository still contains the application code, preprocessing pipeline and analytical logic used during the project.

## Author

**Jun Han**  
BSc Mathematics and Statistics  
University of Manchester