Beating hockey project 2022 - Cosmo Pallarito, February 2022
Run the scripts in the following order:

1. Preproccesor One
2. Preprocessor Two
3. Preprocessor Three
4. Preprocessor Offset
5. Postprocessor One
6. Postprocessor Two
7. NHL Lin Reg v11

The preprocessors prepare the data before the offset file with feature engineering. The offset
file is critical for avoiding target leak in the data.

The data is sourced from:
1. Scraper I built which uses selenium to navigate https://www.hockey-reference.com/
2. Moneypuck and evolving hockey for advanced stats
3. Oddsportal.com

My last regressor achieved an accuracy level of 58.8%
The current best models clock in around 60%
