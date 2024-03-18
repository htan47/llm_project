# Skunkworks project “Extracting Scientific Data From LLMs”

## Goal:
* Extract data for a materials property from an LLM and assess the quality of the database.
* Use the database to construct and assess a machine learning model with MASTML.


## The space to explore
- Properties
- Prompts (including system prompts at the start, chains vs. new prompts) and settings
- Web access
- Multiple LLMs
- The final ML model fit (if useful to demonstrate efficacy of data and enhance its value)

  
## Unsolved challenges
- Methods of assessment (e.g., we often have no ground truth list so will need to very selectively test by hand and compare to existing related databases or high-quality ML models).
  - Random checks vs. google.
  - Checks vs. std database for cases that exist in both LLM and std database.
  - Compare lists from different approaches, maybe take intersections.
  - Build ML model on robust parts and look for outliers.
  - Consider these checks in tranches (first half, second half) and look for trends.
  - Setting up benchmarks for automated testing is essential.
- Optimal approaches to above exploration.
