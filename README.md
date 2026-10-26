# Problem-Set-2-Econ_3916_PS2.ipynb
# The Survey That Wasn't Random
ECON 3916 — Problem Set 2

## Objective
Investigate whether an apparent improvement in survey satisfaction reflects a real population change or a change in who responds.

## Methodology
- Simulated 50,000 users before and after a survey redesign.
- Applied response probabilities that depend on satisfaction, engagement, and support tickets.
- Used bootstrap intervals, coverage simulations, a two-sample test, and power analysis.
- Tested inverse-probability weighting and compared the adjusted estimate with the known population truth.

## Key Findings
- The true population improvement was approximately 0.10 points.
- Respondents showed a 0.72-point improvement, with a 95% bootstrap interval of 0.70–0.74.
- A representative survey would need approximately 1,237 completed responses per group to detect a 0.10-point improvement with 80% power.
- Weighting reduced the post-redesign estimate from 4.309 to 4.137, but its interval of 4.117–4.159 excluded the true population mean of 3.391.
- Larger surveys reduced random variation while substantial nonresponse bias remained.

## Takeaway
Statistical significance and narrow intervals do not guarantee a representative estimate. A consistent probability-sample survey with intensive follow-up of nonresponders would address the underlying data-collection problem.
