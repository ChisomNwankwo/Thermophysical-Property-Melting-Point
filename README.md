## Description

### 🧪 Melting Point Prediction Challenge
Predicting the melting point of organic molecules is a long-standing challenge in chemistry and chemical engineering. Melting point is critical for drug design, material selection, and process safety, yet experimental measurements are often costly, time-consuming, or unavailable.

In this competition, you’ll use machine learning to predict melting points from group contribution features, subgroup counts that represent functional groups within each molecule. Your task is to build models that capture the complex, nonlinear relationships between molecular structure and melting behavior.

Submissions are scored using Mean Absolute Error (MAE) on a held-out test set. Lower is better.

Can you design models that generalize across diverse chemical families and push the limits of data-driven property prediction?

#### Dataset Description

- Total compounds: 3328
- Train: 2662 (80%)
- Test: 666 (20%)

#### Files
- train.csv : Features + target (Tm)
- test.csv : Features only, no target
- sample_submission.csv : Template with columns [id,Tm]

#### Columns

- id : unique ID
- SMILES : molecular string
- Group 1..N : descriptor features
- Tm : melting point (K) [train only]

Additional information hosted on the Machine Learning for Engineers course in the Thermophysical Properties page.
