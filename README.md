# Dataverse-Hack
Insurance claim prediction - Analytic Vidhya

## My approach:
My primary objective was to make the model rich in features. I created a significant number of features and then used feature selection to narrow it down to the best `25`.
I started with 10 fundamental features, but the results were unsatisfactory. Creating new features gave me a good result. I tried out several other classification algorithms, including Random Foreset, GradientBoost, and LGBM, and ultimately settled on `GradientBoost`. The imbalance was addressed by employing `SMOTENN`. SMOTE and other methods were also attempted, but SMOTENN proved to be the most effective.

## Final Standing
- Position: 76th
- score: 0.1684487580

## Limitations:
Due to timing constraints, hyperparameter tweaking was not possible. The final performance is determined by the model's default parameters.

#### Top Approaches:
 - #1 https://docs.google.com/document/d/14CqefxCVxlZjUOG5QCmhIqpXguVVv7_9Ug3l7CI5Bek/edit
 - #2 https://github.com/Santanu7/analytics-vidya-dataverse/blob/main/Dataverse_Claim_Prediction_Sol.ipynb
 - #10 https://github.com/sharma-ji/av_dataverse2022
 - #11 https://github.com/kc113/Dataverse-Hack
 - #12 https://docs.google.com/document/d/1nS5eyYSiv30HlsoCV9s8m3FniUER2kruGbsFYvtelMo/edit#heading=h.215aoooqhg0b
 - #17 https://docs.google.com/document/d/1ZAtjMjigWwK8nusE24Xf7n1kH7aont_V/edit