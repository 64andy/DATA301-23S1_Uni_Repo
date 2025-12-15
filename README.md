# DATA301-23S1
This repository contains my labwork and project from my DATA301 course at the University of Canterbury, during 2023.

Technologies used: PySpark, Jupyter, Google Cloud


## Warning:
The files in this repo are provided <ins>as is</ins>!

This course used Jupyter notebooks, run inside a Google Cloud instance that no longer exists, linked to a billing account without a card. If you want to run the code locally, especially on Windows, it's up to you to get it working.

## Structure:
- **`Labs/Lab[n]`** - Contains the artifacts of the labeled week's lab, including Jupyter notebooks and write-ups. *Does not contain the lab objectives*
- **`Project/`** - Contains this course's final project.
  - **`./DATA301-23S1 - Project Proposal.pdf`** - The proposal I submitted to my lecturer
  - **`./data/`** - The datasets used for this project. They include each recipe's ingredients, and each review left on these recipes, as obtained from Food.com. **Note that none of these are provided in this repo, as they exceed GitHub's 100MB file limit. However, they are still accessable from the URLs inside the project notebook.** The key files are:
    - **`./ingr_map.pkl`** - A map for grouping similar ingredients, so different names for the same thing can be lumped together
    - **`./PP_recipes.csv`** - A pre-processed dataset of recipes from Food.com
    - **`./PP_users.csv`** - A pre-processed dataset of reviews for said recipes
    - **`./RAW_recipes.csv`** - A raw dataset, so we can better understand the above datasets
  - **`./DATA301 [...] Food.com ingredients.ipynb`** - The project notebook itself.

## Project:
My project for this course was to process recipes from Food.com, and to determine what ingredients tended to occur in highly rated recipes, and ingredients in poorly rated recipes. 