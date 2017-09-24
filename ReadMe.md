
# Analyzing Thanksgiving
The project came from the DataQuest mission [Guided Project: Analyzing Thanksgiving Dinner](https://www.dataquest.io/m/219/guided-project-analyzing-thanksgiving-dinner).
The dataset came from [FiveThirtyEight](https://www.fivethirtyeight.com/), and can be found [here](https://github.com/fivethirtyeight/data/tree/master/thanksgiving-2015). 

### The challenge:
Determine how many respondents had no pies, how many had 1 pie, how many had 2, and so on.  The processing for pies will be repeated for desserts.

### The data:

The data for pies and desserts are stored in multiple columns, one for each type of pie (apple, pumpkin, sweet potato, etc), as well as a "None" and two "Other" columns.  Desserts follow the same format.  If a respondent chose a pie or dessert, the name ("Apple", "Pumpkin", "Brownies") is stored for that pie/desseert and that respondent.

### Filtering and Factoring

The first step was to only use the questions about pies and deserts.  I created a new CSV file with all the questions and added a Subcategory column.  This way I could easily find just the questions I was looking for.  The next step was to convert pie and dessert names into counts.  This was done in the functions _calc_pie_counts_ and _calc_dessert_counts_.  Please see the cell documentation for more information.

### Graphing:

I chose side-by-side bar graphs to show the relative numbers of pies and desserts.
