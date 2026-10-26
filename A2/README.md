# A2 — Exploring sources of bias in data

**Dataset 1:** Wikipedia Talk Labels: Toxicity
**Source 1:** https://doi.org/10.6084/m9.figshare.4563973.v2  (pulled 2026-10-25)
**License / terms of use:** CC0 (public domain)(https://creativecommons.org/publicdomain/zero/1.0/) 

**Dataset 2:** Wikipedia Talk Labels: Aggression
**Source 2:** https://doi.org/10.6084/m9.figshare.4267550.v5  (pulled 2026-10-25)
**License / terms of use:** CC0 (public domain)(https://creativecommons.org/publicdomain/zero/1.0/)

**Dataset 3:** Wikipedia Talk Labels: Personal Attacks
**Source 3:** https://doi.org/10.6084/m9.figshare.4054689.v6  (pulled 2026-10-25)
**License / terms of use:** CC0 (public domain)(https://creativecommons.org/publicdomain/zero/1.0/)


## Questions I asked
Part 2: Descriptive Stats
- What is the gender distribution of these workers?
- What is the distribution of the workers by first language?
- What is the distribution of these workers by age group?
- What is the distribution of these workers by education level?

- Do any of the fields in this dataset have missing data? If so, which fields, and what % of the rows contain missing values?
- Re-run the summary statistics from the 4 descriptive stats questions above. How have these summary statistics changed?
- In general, how do the demographics of these workers compare to those of English-speaking internet users overall? Why would it matter if the worker demographics don't match the demographics of the intended end users of the Perspective API?
- Given what you now know about the Wikipedia Talk Corpus, what issues might arise if it was used to train a machine learning-driven "hostile speech detector" that could be used on any website or social media platform?

Part 3: Digging Deeper
- What % of workers who labelled the toxicity dataset do we have demographic data for?
- What % of the comments in the toxicity dataset were labelled by male vs. female-identified workers?
- What % of the comments in the toxicity dataset were labelled by people for whom English is NOT their first language?
- Based on your findings from the three questions above, how might this dataset present a biased view of "toxicity"? How would you expect such biases to impact how the Perspective API performs?
  

## How to re-run
Open `hcde410-a2.ipynb` and run all cells (needs `pandas`).
