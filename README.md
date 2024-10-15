## VelocityX
Deriving Monetization Strategies for VelocityX - An App Enhancing Racing Spectatorship Experience

# Files
data_cleaning_and_analysis.ipynb: The Jupyter Notebook containing the complete data cleaning, exploratory data analysis (EDA), and predictive modeling process.

# Insights
1. Merchandise Purchases Correlation:
Fan Challenges Completed: Users who complete more fan challenges tend to purchase more virtual merchandise. There is a moderate positive correlation between the number of challenges completed and merchandise purchases.
Sponsorship Interactions: Users who interact with more sponsorship ads (clicks) are also more likely to buy virtual merchandise.
Time on Live 360 and Real-Time Chat Activity: These variables had weaker correlations with merchandise purchases, but users who engage more in these activities show slightly higher purchase behavior.

3. Predictive Modeling:
To address the class imbalance where all users in the dataset had purchased merchandise, I reframed the problem to classify users into those who make above-average vs below-average merchandise purchases.
A logistic regression model was trained to predict whether a user will buy above average based on their in-app engagement. The model achieved a baseline accuracy of 65% with balanced precision and recall scores, though improvements are possible.

5. Fan Challenge Proposal: "Predict and Win with Live 360!"
Challenge Concept: Users engage in real-time predictions during race events via the Live 360 feature, predicting outcomes like the fastest lap or most overtakes. Correct predictions earn points, which can be redeemed for discounts or exclusive merchandise.
Incentives: Bonus points are awarded for interacting with sponsorship content (e.g., ad clicks), driving both engagement and sponsorship monetization.
Predicted Outcomes:
Increased Engagement: Users will spend more time on Live 360, boosting real-time chat activity and in-app participation.
Higher Merchandise Sales: Rewarding users for correct predictions with discounts and exclusive items will drive merchandise purchases.
Increased Sponsorship Interactions: By integrating sponsorships into the challenge with points incentives, users will be more inclined to engage with ad content.
