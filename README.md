# .data-science-project

## About Me
Hello, I am LJY, a student of the UM CISC7204 course. I am interested in data analysis and visualization.

## Technical Skills
- Python (pandas, numpy, matplotlib, scikit-learn)
- Jupyter Notebook
- Git / GitHub
- Data cleaning and visualization

## Project Showcase

### Project Title: Palmer Penguins: Morphological Differences Across Species

## Research Question
How do body measurements (bill length, bill depth, flipper length, body mass)
differ across the three penguin species (Adelie, Chinstrap, Gentoo), and can
these features distinguish species?

## Dataset Source and Usage Permission
Palmer Penguins dataset, originally collected by Palmer Station Antarctica LTER
and provided via the seaborn built-in datasets (`sns.load_dataset("penguins")`).
License: CC0 (public domain). No personal or restricted data is included.

## Methods and Tools
- Python 3, pandas for data cleaning and grouping
- matplotlib and seaborn for visualization
- Exploratory data analysis: summary statistics, boxplots, scatterplots

## Key Findings
1. Gentoo penguins have clearly larger body mass and longer bills than Adelie
   and Chinstrap.
2. Bill length vs bill depth separates the three species into fairly distinct
   clusters, suggesting these features are useful for species discrimination.
**Limitation:** The dataset contains only three species from one region and has
missing values; results may not generalize to other penguin populations.

## How to Run the Analysis
1. Install dependencies: `pip install -r requirements.txt`
2. Open `penguins_analysis.ipynb` in Jupyter Notebook
3. Run all cells; figures are saved to `images/`
