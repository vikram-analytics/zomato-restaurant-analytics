# -zomato-restaurant-analytics
restaurant rating analysis using Python, and Power BI

An analysis of 148 Bengaluru restaurants from Zomato, covering data cleaning, exploratory analysis, SQL querying, and a 2-page Power BI dashboard.

## Problem
Understand what drives restaurant ratings and popularity — cost, votes, booking options — using real Zomato listing data.

## Dataset
- 148 restaurants, 7 columns (name, online ordering, table booking, rating, votes, cost for two, listing type)
- Cleaned using Python (Pandas): converted `rate` from string format (e.g. "4.1/5") to numeric, renamed to `rating_out_of_5`, verified no missing values, exported as `Cleaned-zomato-dataset.csv`
- ## Files in this repo
| File | Description |
|---|---|
| zomato-dataset.ipynb | Python notebook — data cleaning and EDA |
| zomato_dashboard.pbix | Power BI dashboard file |
| Cleaned-zomato-dataset.csv | Cleaned dataset used for SQL and Power BI |

## Key Findings
- Average cost for two is ₹418, ranging from ₹100 to ₹950
- Restaurants rated 4.4 and above show a sharp jump in vote counts (avg. 4,642 votes for 4.4-rated restaurants among those with 50+ votes), suggesting rating and popularity reinforce each other at the top end
- Mid-range ratings (2.6–3.5) show much lower and more inconsistent vote counts
- 95% of restaurants in the dataset don't take table bookings (140 of 148 listed as "No")

## About
Built as part of a self-directed transition from IT/Desktop Support into data analytics. Full profile: [github.com/vikram-analytics](https://github.com/vikram-analytics)
