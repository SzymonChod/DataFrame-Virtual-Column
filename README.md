# DataFrame-Virtual-Column
A repository for a simple virtual column creation.

This repository allows for creation of a DataFrame table from two existing tables. 

It handles simple mathematical expressions (allows addition, subtraction and multiplication).

The function checks if arguments follow the set rules and if not returns an empty DataFrame.

## Rules:
- Column lables consist of only letters and underscores.
- Function supports addition, subtraction and multiplication but not other operations.
- If role or column names are incorect, returns an empty DataFrame. 
