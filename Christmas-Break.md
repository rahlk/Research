Progress
---

1. Submitted and updated XTREEs IST paper on arxiv.

2. Worked on Prevalance of Bellwethers paper.
   - Implemented 2 new transfer learners: (1) Transfer Naive Bayes (TNB), and (2) Value-Cognitive Boosting (VCBoost)
   - Bellwether/Transfer Learning on 2 new groups of datasets: (1) Effort Estimation datasets (coc81, mystry1, mystry2, nasa93, cocomo), and (2) 4 communities of code smells dataset (DataClass, LongMethod, FeatureEnvy, GodClass)
   - Results [here](https://github.com/bellwethers-in-se/documentation/blob/master/REPORT-01-07-2017.md)
   - TL;DR **There are bellwethers in all 3 communities of datasets**. **TCA+ is not always the best transfer learner.** **This is only true in defect datasets. Bellwether method works best in effort and code smells datasets.**

3. Housekeeping tasks:
  
  + Fixed the high (pd, pf) issue in defects dataset. 
    + I used the P(detection) thresolds of prediction from the Learners from sklearn's `clf.predict_proba(X,` `y)` to obtain thresholds and applied a manual cutoff.
    + Also, there was an issue with DE tuning, which was also fixed.
    + Now the PDs and PFs are somewhat consistent with Table 5 in the IST paper.
  + Cleaned-up code and created a new repository with clean code [here](https://github.com/bellwethers-in-se).
  
