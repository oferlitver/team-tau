# Pandas cheat sheet
- read a csv: `pd.read_csv("my_path")`
- delete a column: `df.drop([list], 1)` or `df.drop(my_col, 1)`
- manipulating specific column: `my_series.map(lambda/func)`
- count number of NA's: `isnull().sum()`
- contingency table: `pd.crosstab(a, b)` or `pd.crosstab(a, [b, c, d...])
