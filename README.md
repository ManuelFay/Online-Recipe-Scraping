# Online Recipe Scraping

Repository containing information scraped on a cooking recipe website online. The idea was to get an understanding of culinary habits from around the world to be able to find further correlations down the road.

The scrap bot is contained in the Jupyter notebook and collects for each country, a list of the most popular recipes with their rating, popularity, nutrition information and ingredients. It then parses the ingredient list to get a sense of the quantities for each ingredients and detects the vegetables from these recipes. This is useful to compute a Nutrition Score for each recipe using the french government's "NutriScore" formula.
