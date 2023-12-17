# avocado-toast-a-supply-chain-analysis

This is a project that provide by Datacamp. What's in an Avocado Toast: A Supply Chain Analysis? 

You're in London, making an avocado toast, a quick-to-make dish that has soared in popularity on breakfast menus since the 2010s. A simple smashed avocado toast can be made with five ingredients: one ripe avocado, half a lemon, a big pinch of salt flakes, two slices of sourdough bread and a good drizzle of extra virgin olive oil. It's no small feat that most of these ingredients are readily available in grocery stores. 

In this project, you'll conduct a supply chain analysis of three of these ingredients used in an avocado toast, utilizing the Open Food Facts database. This database contains extensive, openly-sourced information on various foods, including their origins. Through this analysis, you will gain an in-depth understanding of the complex supply chain involved in producing a single dish. 

Three pairs of files are provided in the data folder:
- A CSV file for each ingredient, such as `avocado.csv`, with data about each food item and countries of origin
- A TXT file for each ingredient, such as `relevant_avocado_categories`, containing only the category tags of interest for that food.

Here are some other key points about these files:
- Some of the rows of data in each of the three CSV files do not contain relevant data for your investigation. In each dataset, you will need to filter out rows with irrelevant data, based on values in the `categories_tags` column. Examples of categories are, fruits, vegetables, and fruit-based oils. Filter the DataFrame to include only rows where `categories_tags` contains one of the tags in the relevant categories for that ingredient.
- Each row of data usually has multiple categories tags in the `categories_tags` column.
- There is a column in each CSV file called `origins_tags` with strings for country of origin of that item.

After completing this project, you'll be armed with a list of ingredients and their countries of origin, and be well-positioned to launch into other analyses that explore how long, on average, these ingredients spend at sea.

[def]: avocado_wallpaper.jpeg