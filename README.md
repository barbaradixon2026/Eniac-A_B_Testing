## Eniac-A_B_Testing

## Overview
This Project was completed during my Data Analytics training at WBS Coding School. The project demonstrates foundational and intermediate A/B testing sills. It involved performing a chi-square test with data from Eniac to determine which variant of the button has the most clicks

## Objective
The goal of this is to showcase how A/B testing leads to evidence-based decision making rather than relying on 'gut feelings.'

## Tools
- Python
- COLAB Notebook

## Business Problem
Based on the feedback and reviewing some successful colour choices from previous ad-campaigns, the UX team asked web-design for the three new variations of the 'SHOP NOW' button. the decision was reached to test all four versions of the button:

White “SHOP NOW”
Red “SHOP NOW”
White “SEE DEALS”
Red “SEE DEALS”

It was decided that for a version to be considered superior, there must be **statistical significance** in the click-through rate. The hypotheses to be tested in the experiment are the following:

**Null Hypothesis:** all versions have the same CTR.
**Alternative Hypothesis:** there is a difference in the CTR for the different versions.

## Analysis Areas
- **Chi-squared test:** Tested if the differences in click-through rate for the different variants is statistically significant.
- **Post-Hoc Test:** Used the Bonferroni Adjustment for pairwise comparisons to identify the top performing versions.

## Conclusion
It is evident that the version with the highest click-through rate, Version_C, exhibits a statistically significant difference when compared Versions B and D, but not to Version_A, which possesses the second-highest click-through rate. As a result, declaring a clear winner based on post hoc tests becomes challenging, therefore we can only say that both Version_C and Version_A are the winners.

## Recommendation
if a definitive winner is required, additional steps need to be implemented. This is where we transition from the realm of statistics to the business world. The following actions can help in determining the version to be featured on the website in the future:

Consider other metrics alongside click-through rate.
Incorporate qualitative research findings.
Seek input from subject-matter experts.
Redesign the experiment and conduct it once more.

## Key Learning
Through this project, i developed the ability to use A/B testing can lead to an **evidence based decision making.**
