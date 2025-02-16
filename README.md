# Unlocking Airbnb’s European Secrets with Power BI – A Data Storytelling Journey

## Executive Summary
This project demonstrates the transformative power of storytelling in data visualization by reimagining an Excel-based AirBnB analysis into a narrative-driven Power BI dashboard. Using identical data from ten European capitals, this implementation showcases how thoughtful dashboard design and strategic storytelling can convert raw data into compelling insights. The project explicitly contrasts with its Excel counterpart, demonstrating how shifting from a traditional multi-chart approach to a guided analytical narrative significantly enhances data communication and actionability.

## Business Problem
Modern organizations face a critical challenge: transforming data into actionable insights. While our companion Excel project demonstrated technical proficiency, it also revealed the limitations of traditional dashboard design. This Power BI implementation addresses these limitations by answering:
How can we transform the same AirBnB data into a compelling narrative that guides stakeholders to clear, actionable conclusions?
The project tackles this challenge by:
- Converting disconnected visualizations into a coherent story.
- Guiding users through logical analytical progression.
- Maintaining technical depth while improving accessibility.
- Demonstrating the evolution from data presentation to data storytelling.

## Methodology
To tackle these challenges, I implemented the following steps:
- Data Integration: Replicated Excel's Power Query data preparation, where I merged weekday and weekend CSV files for each city, appending “day” and “city” columns to maintain critical context.
- Data Cleaning & Transformation: I standardized column names, eliminated duplicate records, and converted Boolean values into user-friendly “Yes/No” indicators. Continuous variables like distance from the city centre and the nearest metro station were categorized into defined ranges (0-1 km, 1-2 km, 2-3 km, and 3+ km) to enhance segmentation.
Dashboard Design with Storytelling: The dashboard is structured into three thematic sections:
    - Key Metrics and Insights: This section features a horizontal bar chart (cities sorted by average price), a summary table (average, maximum, and minimum prices), a pie chart (room type breakdown), and a vertical bar chart (average price by accommodation capacity). Accompanying narrative text provides context, explaining market dynamics such as why Amsterdam is overall expensive and how capacity influences pricing.
    - City Centre and Metro Proximity Insights: Two stacked 100% horizontal bar charts illustrate the percentage distribution of listings across distance ranges. Narrative insights here help interpret the implications of location on pricing and customer satisfaction.
    - Customize Your Analysis: Interactive slicers allow users to filter data by city, room type, superhost status, day type, and more—empowering users to tailor the narrative to their specific needs.

This methodology ensures that the final dashboard not only presents data but also tells a story—guiding users to actionable business recommendations.

## Skills
This project demonstrates proficiency in:
- Power BI & Power Query: Advanced techniques for data integration, cleaning, and transformation.
- Dashboard Development: Creating interactive, multi-layered dashboards that combine various visualization types with narrative text.
- Data Visualization: Designing bar charts, pie charts, tables, and interactive slicers to clearly communicate complex data.
- Storytelling in Data: Integrating contextual narratives within the dashboard to convert raw data into actionable insights.
- Business Analytics: Translating data findings into strategic business recommendations, ensuring that analytical insights lead to effective decision-making.

## Results & Business Recommendation
Key Findings (they are almost the same as those of the Excel project):
- Pricing Insights: Amsterdam emerges as the most expensive city overall, while Athens, despite high maximum prices, shows the lowest average pricing.
- Market Composition: Approximately two-thirds of listings are entire homes or apartments, reflecting a strong market preference for self-contained accommodations.
- Capacity Impact: While pricing remains similar for 2- or 3-person accommodations, there is a significant price jump for listings designed for 4-person groups.
- Location Dynamics: Analysis shows that while nearly 75% of listings are located very close to metro stations, their proximity to city centres varies significantly—impacting both pricing and customer satisfaction.

Business Recommendations (they are almost the same as those of the Excel project):
- Adopt Narrative-Driven Dashboards: Integrate storytelling elements to ensure that dashboards transform data into clear, actionable business strategies. This approach can significantly enhance decision-making compared to generic visualizations.
- Optimize Pricing Strategies: Focus on high-demand markets like Amsterdam for premium pricing, and consider market repositioning in cities like Athens to capture emerging opportunities.
- Tailor Marketing Initiatives: Use insights on accommodation types and capacity to design targeted marketing campaigns that resonate with specific customer segments.
- Enhance Operational Efficiency: Utilize location-based insights to adjust resource allocation, particularly by targeting areas with high metro proximity or varied access to city centres.

This project demonstrates how the same data, when presented through a storytelling lens, transforms from simple visualization into actionable intelligence. The evolution from Excel to Power BI represents not just a tool change, but a fundamental shift in how we communicate with data.
