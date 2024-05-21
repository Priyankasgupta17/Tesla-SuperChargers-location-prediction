**Data Exploration**:
Two datasets were used: electric vehicle (EV) population and charging station locations.
Data visualization techniques (density plots, heatmaps, tables) revealed a correlation between EV density and existing charging stations. Higher density areas were typically in the northwestern part of the state, around Seattle.

**Data Preprocessing:**
The datasets were combined, focusing on relevant features like zip code, number of EVs, and existing charging stations.

**Data Mining Techniques:**
Linear regression: Analyzed the relationship between EV count and charging stations. A positive correlation (β1 = 0.0157) was found, indicating more stations in areas with more EVs. The high R-square (0.9020) suggests the model effectively explains this relationship.

**Clustering:**
K-means clustering with SAS and Python identified four distinct groups of zip codes based on EV count and gas station count. Each cluster represented a different market segment:

Cluster 0: Well-balanced market (average 64 vehicles per gas station)

Cluster 1: Emerging market with lower demand (average 50 vehicles per gas station)

Cluster 2: High potential for EV stations (average 159 vehicles per gas station)

Cluster 3: High-demand urban areas (average 62 vehicles per gas station)

**Key Findings:**

Cluster 3 had the highest average EV density (1774.94 vehicles per zip code) and electric vehicle range (87.41 miles), indicating a mature market.

Cluster 2 had a lower EV density (284.90 vehicles per zip code) but the highest ratio of EVs to charging stations (159.24), suggesting a high unmet demand for charging infrastructure.

**Recommendations:**
Based on the analysis, Tesla should prioritize these two clusters for Supercharger deployment:

Cluster 3: Ideal for targeting an established EV market with high traffic and existing demand.

Cluster 2: Potential for serving an underserved area with a high potential for future growth.

Further research on specific zip codes within these clusters is recommended, considering factors like electric grid capacity and nearby highways.
