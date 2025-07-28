# Objective
Build a clean, curated dataset from TMDB’s raw movie records to analyze box office performance trends, actor profitability, and genre-specific success over time. The project aims to support both historical analysis and predictive modeling for film revenue forecasting and strategic decision-making

# Overview
Starting with over 700,000 raw movie records from The Movie Database (TMDB), a rigorous data wrangling process was undertaken using Python to extract, clean, and transform the dataset. The cleaned dataset was refined to 9,678 movies with reliable values for revenue, budget, cast, and crew information.

Key calculated metrics included:

Gross Profit = Revenue – Budget

Profit Percentage = (Profit / Budget) × 100

The data was then visualized using Tableau, where filters and dashboards were created to distinguish:

-Animated vs. Conventional films

-Profitability by actor, genre, and release year

-Director and production studio trends

-Top-grossing movies and franchises

The end product provides a versatile analytics-ready dataset that supports stakeholders in identifying high-performing genres, evaluating casting decisions, and modeling ROI.

# Tech Stack
Programming Language: Python

Libraries: pandas, numpy, scikit-learn, matplotlib

Tools: Jupyter Notebook, Tableau

# Key Insights

1.Actor Profitability – A small subset of actors (e.g., franchise stars) consistently appeared in the most profitable films, especially in action and animation genres.

2.Genre Trends – Animated films had fewer releases but often delivered stronger ROI compared to conventional genres, especially in family segments.

3.Year-over-Year Patterns – Major spikes in box office revenue aligned with blockbuster releases, franchise launches, and holiday seasons.

4.Budget vs. Success – High-budget films didn’t guarantee profitability. Many mid-budget productions outperformed on ROI due to controlled costs.

5.Director and Crew Influence – Repeated collaborations between certain directors and cast members resulted in consistently higher earnings, indicating the value of proven creative teams



# Conclusions & Recommendations

1.Prioritize Mid-Budget Films – Focus on genres and themes that historically yield strong profit margins even with lower budgets.

2.Leverage Proven Talent – Use data to identify high-performing actors and directors, especially those with repeated box office success.

3.Genre-Driven Strategy – Invest strategically in animated and family-oriented films for steady, long-term profitability.

4.Use Data for Greenlighting – Apply historical ROI analysis to inform funding decisions for upcoming productions.

5.Future Enhancements – Integrate streaming data, audience ratings, and social media buzz to enrich predictive models of movie performance
