**Authors:** 

Abel Aleu Chol Garang

Carolyne Githenduka

Collins Wambu

Bobbin Bodo

Yvonnie Muthoni


# An Analytical Deep-Dive into the Film industry to get ationable insights so as to venture in the film business

## Business Problem
Our company now sees all the big companies creating original video content and we want to get in on the fun. We have decided to create a new movie studio, but we don’t know anything about creating movies. We exploring what types of films are currently doing the best at the box office. We then translate those findings into actionable insights that the head of our company's new movie studio can use to help decide what type of films to create.

## Dataset
- Source: The MovieDB, The Numbers, IMDB SQLite Database, Box office Mojo (CSV) file
- Scope: Film budget, runtime, income gross and genre
- Focus: Films

A comprehensive dataset containing film productio. The project focuses on identifying patterns in successes and failures of film in the film industry.

## Methodology
The project followed a structured, step-by-step approach to transform raw film data from different datasets into actionable business insight:

1. Dropped columns not relevant for our analysis
2. Removed duplicates
3. Converting expenditure and revenue columns to numeric values
4. Handled missing values in critical columns 
5. Standardization
6. Merging datasets for analysis

This methodology allowed different datasets to be compared objectively using consistent criteria.

## Key Metrics
To capture film production_budgets, gross income against several key metrics such as:

- runtime minutes
- genres
- studio
- time of release

Together, these metrics provide a multi-dimensional view of film production and results.

## Key Findings

- High budgets do not guarantee high ROI. 
![alt text]()

- Genres like Animation, Adventure, and Action dominate worldwide revenue.

- Foreign markets contribute a significant portion of total revenue.

- Longer runtime do not necessarily increase profitability.

- Higher IMDb ratings are associated with higher revenue, but only for sufficiently popular films.

## Recommendations
Based on the analysis, the following actions are recommended:
- Invest in high-quality animation or franchise-able sci-fi/adventure stories. These require higher budgets but offer the largest absolute financial gains.
- Produce low-to-mid-budget mystery or thriller films (e.g., the Blumhouse model). These are "safer" bets for consistent returns on smaller capital outlays.
- Allocate a significant portion of the total budget to marketing and "hype" generation, as popularity is more closely tied to profit than the rating itself.

These steps will help the company make informed decisions.

## Limitations
1. Survivorship Bias

The dataset primarily tracks "final" clean movies that likely had theatrical releases and recorded box office data.

    The Risk: It may exclude thousands of indie or direct-to-streaming films that failed to secure distribution or lost their entire investment. This can make the industry look more profitable than it actually is by only looking at the "winners" who made it to the database.

2. Reliance on Historical Data (2010–2018)

The film industry has undergone a seismic shift since 2018.

    The Rise of Streaming: The data does not account for the "Netflix effect" or the shift toward Day-and-Date streaming releases. Success metrics for platforms like Disney+, Netflix, or HBO Max are based on "minutes viewed" and subscriber retention, not box office profit.

    Post-Pandemic Behavior: Audience habits changed significantly after 2020. Mid-budget dramas and comedies that performed well in this dataset now struggle more in theaters than they did five years ago.

3. The "Causality vs. Correlation" Trap

    Budget & Profit: While high budgets correlate with high profits, a high budget does not cause profit. Huge investments in films like Justice League or John Carter (which may be outliers) prove that capital alone doesn't guarantee success.

    Genre Popularity: The high profit for Animation is heavily skewed by a few massive "tentpoles" (Pixar, Illumination). A new studio entering the animation space will face much higher barriers to entry than a studio producing a low-budget thriller.

4. Missing Cost Variables

The "Profit" calculation in this dataset typically uses: (Domestic+ForeignGross)−ProductionBudget. This is an oversimplification:

    Marketing Costs (P&A): Big-budget films often spend an additional 50% to 100% of their production budget on global marketing, which is not reflected here.

    Theatrical Split: Studios generally only keep about 50% of the domestic box office and 25%–40% of the international box office (the rest goes to the theaters).

    Participation & Residuals: High-profile actors and directors often take "points" on the back end, further reducing the studio's actual take-home profit.

5. Lack of Qualitative Data

Financial data cannot measure the "Cultural Zeitgeist."

    Brand Equity: A movie might lose money in theaters but build a massive brand that generates billions in toys, theme park attractions, and sequels (e.g., Cars).

    Star Power and IP: The data doesn't explicitly flag which movies are based on existing Intellectual Property (IP) versus original scripts, which is currently the single biggest driver of studio greenlighting.

6. Geographical Nuance

The data aggregates "Foreign Gross," but the international market is not a monolith.

    Market Restrictions: Performance in China—the world’s second-largest market—is subject to strict quotas and censorship that this data cannot predict.
    
    Cultural Specificity: A comedy that performs well in the US might have zero "travelability" in Europe or Asia, whereas Action and Animation translate across cultures easily.

## Future Work
To overcome these limitations, the next step should be to supplement this quantitative analysis with qualitative market research, specifically focusing on current streaming trends (2021–2024) and social sentiment analysis.

## Tableau Visualization link
**[[Click here for an interactive version of the analysis available on Tableau:](http://public.tableau.com/views/phase-2-project-group-one-Tableau/MovieInsightStroytelling?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)]**

