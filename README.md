#Objective
Develop an interactive and cleaned movie performance dataset from TMDB records to analyze box office trends, actor profitability, and genre-specific success over time. The goal is to enable insights into what drives financial performance in films and support historical and predictive modeling for industry stakeholders.

#Overview
Starting with a raw dataset of over 700,000 movies from The Movie Database (TMDB), a rigorous data cleaning process reduced the set to 9,678 high-quality movie entries. The data was enriched with calculated metrics such as:

Gross Profit = Revenue – Budget

Profit Percentage = (Profit / Budget) × 100

Python was used to handle all preprocessing and feature creation, with libraries like pandas, numpy, and matplotlib. A final Tableau dashboard was built to visualize trends, apply filters by genre (animated vs. conventional), and spotlight actors and crew contributing to high-revenue films.

Key steps included:

-Removed movies with missing or zero revenue and budget

-Parsed JSON-like nested data for cast, crew, genres, and keywords

-Engineered features for profitability and revenue benchmarks

-Built Tableau filters for production countries, genres, and top-grossing actors

-Visualized historical revenue and profitability trends by year

#Key Insights
1.Actor Profitability – Certain actors consistently featured in high-grossing films, especially in franchise or action genres.

2.Animated vs. Conventional – Animated films showed high profitability despite smaller counts, emphasizing their family-friendly repeat viewership appeal.

3.Yearly Revenue Trends – Box office revenue peaked in select blockbuster years, showing strong correlation with franchise release cycles (e.g., Marvel, Star Wars).

4.Budget vs. Profitability – Larger budgets didn’t always translate to higher profit margins; mid-budget films often yielded stronger ROI.

5.Director Impact – Top directors showed a repeatability pattern in successful films, especially in action, sci-fi, and animation genres.

Conclusions & Recommendations
1.Investor Strategy – Mid-budget films in family and animation genres offer lower risk and consistently high ROI.

2.Casting Decisions – Studios should prioritize actors and directors with proven box office success, particularly in high-earning genres.

3.Genre Focus – Continue to invest in sequels and franchises, as they show reliable profitability patterns across years.

4.Data-Driven Production – Use historical trends to forecast genre-based revenue and assist in greenlighting future projects.

5.Future Work – Extend the model to include streaming performance data, sentiment analysis from reviews, or use ML models for predictive box office modeling.

#Tech Stack
Programming Language: Python

Libraries: pandas, numpy, scikit-learn, matplotlib

Tools: Jupyter Notebook, Tableau
